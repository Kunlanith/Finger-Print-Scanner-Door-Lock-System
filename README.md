# Fingerprint Scanner Door Lock System

## Overview
The **Fingerprint Scanner Door Lock System** is a high-security access control solution that combines **biometric fingerprint scanning** with **RFID** technology to provide keyless entry. This system allows users to unlock a door by scanning their fingerprint, with RFID as a backup in case of failure. The system provides an efficient and secure alternative to traditional locks, reducing the risk of unauthorized access and eliminating the need for physical keys.

## Features
- **Fingerprint Authentication**: Uses a **DY50 Capacitive Fingerprint Scanner** to capture and verify fingerprints.
- **RFID Backup**: If the fingerprint scan fails, the system allows access through an RFID keycard.
- **Automatic Locking**: The solenoid lock is activated when a valid fingerprint is detected and automatically locks after 5 seconds.
- **Status Display**: Displays the authentication status (e.g., "Access Granted" or "Access Denied") on an LCD screen.

## Components
- **Fingerprint Scanner**: DY50 Capacitive Fingerprint Sensor.
- **RFID Reader**: For backup access via RFID keycards.
- **Solenoid Lock**: For controlling the door lock mechanism.
- **Arduino**: Acts as the microcontroller, controlling the system's operations.
- **LCD Screen**: Displays status messages to the user.
- **Power Supply**: Powers the system and its components.

## How It Works
1. **Fingerprint Scan**: The system captures the fingerprint from the user and compares it with stored templates.
2. **RFID Backup**: If the fingerprint is not recognized or the scanner is unavailable, the RFID card can be used to gain access.
3. **Solenoid Lock**: Once access is granted, the solenoid lock is activated, allowing the door to open. The lock automatically engages again after a short delay.
4. **Status Display**: The LCD screen shows whether the fingerprint was successfully matched or if the RFID card is needed.

## Team Members
- **Akarat Pattara-anuvong**
- **Kunlanith Busabong**  
- **Saranya Vichakyotin**  
- **Peerapat Benjapornpong**  
- **Dome Tanvisets**  
- **Pornpatara Boonyapisitsopa**

## Installation

1. **Hardware Setup**: Connect the **DY50 Fingerprint Scanner**, **RFID Reader**, **Solenoid Lock**, and **LCD screen** to the **Arduino** according to the wiring diagram.
2. **Software**: Upload the Arduino code to the board, which will handle fingerprint scanning, RFID reading, and lock control.
3. **Power Supply**: Ensure the system is powered with an adequate 12V power supply.

## Results
- **Fingerprint Authentication**: The system accurately verifies fingerprints with a success rate of 83.33%.
- **RFID Backup**: Provides a reliable secondary access method with 100% accuracy.
- **Security**: Reduces the risk of unauthorized access and ensures convenient keyless entry.

## Future Work
- **IoT Integration**: Add remote monitoring and control via mobile apps.
- **Enhanced Fingerprint Detection**: Implement algorithms to improve fingerprint recognition accuracy.
- **Expanded User Capacity**: Support more users by storing additional fingerprint templates.
