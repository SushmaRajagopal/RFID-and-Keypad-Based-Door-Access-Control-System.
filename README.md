# RFID-and-Keypad-Based-Door-Access-Control-System.

# Overview
This project implements a security access control system that combines RFID card authentication and a keypad password for door access. The system utilizes an Arduino, RFID scanner, keypad, servo motor, LCD display, and buzzer to provide a comprehensive access control solution.

# Features
RFID card authentication.
Keypad password entry.
Servo motor control for door locking and unlocking.
LCD display for user feedback.
Buzzer for audible feedback.
Automatic door closure after a specified time.

# Components
Arduino Board
RFID Scanner
Keypad
Servo Motor
LCD Display
Buzzer

# Setup
1. Connections:

Connect the RFID scanner, keypad, servo motor, LCD display, and buzzer to the Arduino board according to the provided circuit diagram.

2. Arduino IDE:

Install the Arduino IDE if not already installed.
Upload the scanner.ino and keypad.ino files to the Arduino board.

3. Libraries:

Make sure to install the required libraries for RFID, Keypad, LiquidCrystal, and Servo.

4. Configure:

Define valid RFID tag IDs in the scanner.ino file.
Set the master password in the keypad.ino file.

# Usage
1) RFID Authentication:

Present a valid RFID card/tag to the scanner.
If the RFID tag is valid, the door will unlock, and the LCD will display a success message.

2) Keypad Authentication:

Enter the correct password using the keypad.
If the password is correct, the door will unlock, and the LCD will display a success message.

3) Automatic Door Closure:

The door will automatically close after a specified time if not opened.
