# openobd2

Open OBD-II (to USB) adapter.

### Details

- Supports both CAN and CAN-FD transports
- Supports the J1850 transport (planned)

- Possible ELM327 support (nice to have, not planned right now)
- Possible autonomous SD-card data logging support (nice to have, not planned right now)
- Possible Bluetooth, BLE and/or WiFi connection support (nice to have, not planned right now)

### Hardware

- MCU: EFM32? LPC1500?
- CAN Transceiver: TCAN4551 (w/ possibility to upgrade to TCAN4550 if needed)
- J1850 Transceiver: Drive via MCU directly (planned)

### Software

- Linux CAN driver
- Custom HID-based communication protocol? (OpenInput?)
- OpenXC support (nice to have, not planned right now)

