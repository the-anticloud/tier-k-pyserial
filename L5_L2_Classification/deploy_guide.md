# Deploy Guide — K_PYSERIAL
**Tier:** TIER_9_ROBOTICS_IOT | **Stack:** Python 3.11, pyserial 3.5+, PAX 27B, AIOSS_FORMAT
**Air-gap capable after initial setup.**

## Prerequisites
Python 3.11+, pyserial 3.5+. Any serial device. USB-to-UART adapter if needed.

## Environment
4GB RAM. Any OS. USB-to-serial adapter for non-native serial ports.

## AIOSS Integration
```bash
aioss init --module K_PYSERIAL --output ./k_pyserial.aioss
aioss append --chain ./k_pyserial.aioss --payload ./output.bin --module K_PYSERIAL
aioss verify --chain ./k_pyserial.aioss
```

## Air-Gap Setup
```bash
pip download -r requirements.txt -d ./wheels/
pip install --no-index --find-links ./wheels/ -r requirements.txt
```

## PAX 27B Harness Wiring
```python
from anticloud_pax import PAXHarness
harness = PAXHarness(
    model_path="./pax-27b-q4.gguf",
    module="K_PYSERIAL",
    aioss_chain="./K_PYSERIAL.aioss",
    classification="L5_NARROW_L2_GENERAL"
)
result = harness.process(input_data)
```

## Verification
```bash
aioss verify --chain ./K_PYSERIAL.aioss --verbose
python -m K_PYSERIAL.tests.smoke
```
