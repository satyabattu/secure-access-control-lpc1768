# Secure Access Control System (LPC1768)

Embedded secure access system implemented on the LPC1768 (ARM Cortex-M3),
simulating a real-world door locking mechanism using relay actuation.

## Tech Stack
- LPC1768 (ARM Cortex-M3)
- C
- GPIO
- USB Serial Communication

## Overview
The system grants or denies access based on serial input via a USB terminal.
An LED provides visual feedback, while a relay simulates physical door unlocking.

## Demo
A short hardware demonstration video showing LED feedback and relay actuation
is available in the `media/` directory.

## Documentation
Design notes and supporting reports are available in the `docs/` directory.

## Limitations
- Access control uses simple serial input and does not implement secure authentication.
- No logging of access attempts or timestamps.
- System operation depends on USB serial communication.

## Future Improvements
- Upload embedded C source code (`main.c`)
- Add keypad or RFID-based authentication
- Implement EEPROM or SD-card logging
- Enable standalone or wireless operation

## Notes
This project was developed as part of an Embedded Computing module and focuses on
low-level I/O handling, system design, and hardware constraints.
