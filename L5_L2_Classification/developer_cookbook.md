# Developer Cookbook — K_PYSERIAL
**Stack:** Python 3.11, pyserial 3.5+, PAX 27B, AIOSS_FORMAT
**Domain:** PySerial: serial communication backbone for Anticloud IoT hardware interfaces

## Serial sensor reading
```python
from k_pyserial import AnticloudSerialReader

reader = AnticloudSerialReader(
    port="COM5",
    baud=9600,
    protocol="NMEA",  # GPS protocol parser
    pax_model="./pax-27b-q4.gguf",
    aioss_chain="./pyserial.aioss"
)

for frame in reader.stream():
    parsed = reader.parse(frame)
    interp = reader.pax_interpret(parsed)
    print(f"GPS: {parsed.lat:.6f}N, {parsed.lon:.6f}E")
    print(f"PAX: {interp}")
```

## Raw serial read
```python
reader = AnticloudSerialReader(port="COM5", baud=115200)
data = reader.read_bytes(n=64)
```

## AIOSS Chain Append
```python
import hashlib, time

def aioss_append(chain_path, payload: bytes, module_id: str):
    entry_hash = hashlib.sha3_256(payload).digest()
    ts = int(time.time_ns()).to_bytes(8, 'big')
    with open(chain_path, 'rb') as f:
        f.seek(-32, 2); prev_hash = f.read(32)
    new_hash = hashlib.sha3_256(prev_hash + entry_hash + ts).digest()
    with open(chain_path, 'ab') as f:
        f.write(ts + entry_hash + new_hash)
    return new_hash.hex()
```
