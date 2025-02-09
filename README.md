# Smart Safe
The Smart Safe is a secure storage system that can be unlocked using a keypad passcode or fingerprint authentication. This prototype, built using Arduino, allows for quick development and testing.

Hardware Components
Microcontroller: Arduino Uno
Input Modules: 4x4 Keypad, Fingerprint Sensor
Output Modules: LCD Display, Buzzer, LED
Lock Mechanism: Servo Motor
Power Supply: 5V Adapter

How It Works
The user enters a passcode on the keypad OR scans a fingerprint for authentication.
If verified, the safe unlocks (servo motor activates).
If authentication fails, the system gives a warning (buzzer & LED).

Next Step:
Transition from Arduino board to a standalone ATmega328P microcontroller.
