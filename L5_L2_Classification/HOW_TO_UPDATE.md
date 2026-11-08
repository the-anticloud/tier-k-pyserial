# How to Update — K_PYSERIAL
**Platform:** Anticloud | **IP:** USPTO pending 2026, Anticloud FZ LLE, 0-1.gg

## Module: K_PYSERIAL
Domain: PySerial: serial communication backbone for Anticloud IoT hardware interfaces


## Update Procedure
1. Backup current state
2. Test in api-oss-labs sandbox
3. `pip install --upgrade anticloud-k_pyserial`
4. `python -m k_pyserial.tests.smoke`
5. `aioss verify --chain ./k_pyserial.aioss`
6. Monitor 30 min via api-oss-monitor

## Rollback
```bash
pip install anticloud-k_pyserial==<previous>
python -m api_oss_backup restore --archive ./backups/<latest>
```

## Weight Updates
PAX 27B weight updates are signed by Anticloud FZ LLE:
```bash
anticloud tool verify-weights --model ./pax-27b-q4-new.gguf --sig ./pax-27b-q4-new.sig
```
