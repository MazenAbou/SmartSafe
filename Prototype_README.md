# Smart Safe
The Smart Safe is a secure storage system that can be unlocked using a keypad passcode. This prototype, built using Arduino, allows for quick development and testing.

Hardware Components
Microcontroller: Arduino Uno
Input Modules: 4x4 Keypad.
Output Modules: LCD Display, Buzzer, LEDs
Lock Mechanism: Servo Motor
Power Supply: 5V / 12V Adapter

How It Works
The user enters a passcode on the keypad.
If verified, the safe unlocks (servo motor activates).
If authentication fails, the system gives a warning (buzzer & LED).

Next Step:
Transition from Arduino board to a standalone ATmega328P microcontroller, adding a card reader, and approach sensor (or similar).
