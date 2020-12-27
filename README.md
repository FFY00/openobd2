# openobd2

Open OBD-II (to USB) adapter.

### Details

##### Physical transports
- ISO 15765-4 CAN, w/ CAN-FD support
- SAE J1850 PWM (planned)
- SAE J1850 VPW (planned)
- ISO 9141-2 (K-line) (planned)
- ISO 14230-4 (KWP) (planned)

##### Features
- Custom communication protocol for OBD-II data
- Raw CAN access
- Possible ELM327 support (nice to have, not planned right now)
- Possible [OpenXC](https://github.com/openxc/openxc-message-format) support (nice to have, not planned right now)

##### Operation modes
- USB connection support
- Possible Bluetooth and/or BLE connection support (nice to have, not planned right now)
- Possible WiFi connection support (nice to have, not planned right now)
- Possible autonomous SD-card data logging support (nice to have, not planned right now)

### Hardware

- MCU: SAME51
- CAN transceiver: MCP2561
- K-line transceiver: TLIN1027

### Software

- Linux CAN driver
- Python library to interface with the custom protocol
