# L5 Narrow / L2 General Classification — K_PYSERIAL
**Platform:** Anticloud | **Tier:** TIER_9_ROBOTICS_IOT | **PAX:** 27B
**IP:** USPTO pending 2026, Anticloud FZ LLE, 0-1.gg | **License:** Apache-2.0

## L5 Narrow
K_PYSERIAL provides the serial communication backbone for Anticloud IoT: connecting to UART/RS-232/RS-485 devices, parsing protocol frames, and AIOSS-chaining serial data. Narrow scope: Anticloud serial-connected IoT hardware.

## L2 General
L2 General: K_PYSERIAL is the universal serial I/O for all Anticloud IoT hardware. GPS modules, industrial sensors, motor controllers, and programming adapters all use K_PYSERIAL in Anticloud.

## PAX 27B Integration
PAX 27B receives serial data via K_PYSERIAL and generates structured interpretations: 'GPS NMEA: $GPRMC valid, position 51.5074N 0.1278W, speed 0.0 kt — device stationary at London coordinates.'

## AIOSS Audit Chain
Every serial session (port hash + baud config hash + frame data hash + PAX interpretation) is chained: H_n = SHA3-256(H_{n-1} || entry_hash_n || timestamp_n).
Offline-verifiable, tamper-evident, zero cloud dependency.

## Regulatory / Compliance
No external regulatory. IEC 61508 (safety-critical serial). IEC 62443-4-2.
