# ddrlegobrick
My custom RC brick for Lego Power Functions and C+ motors. Support all current and previous generation Lego Power Functions and Control+ motors using Bluetooth 4.2.

## Supports:
1. Communication with smartphone
2. Dualshock 3/4
3. Xbox Controller

## Branching:
### Firmware (branch: master)
- Designed in Visual Studio Code w/ PlatformIO
- C++ firmware using Arduino-core for ESP32
- Must be flashed as ESP32 Thing Plus

### Revision V1 (branch: hardware)
- ESP32-WROOM-E (16MB version required)
- 4x DRV8833
- 1x PCA9685
- Support for Power Functions only

### Revision V2 (branch: hardware_v2)
- Support for C+ and PF 
