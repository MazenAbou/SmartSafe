Smart Safe Project
Overview:
The smart safe is for anyone with important documents or stuff who wants to keep them away from their roommate, siblings, parents, kids, or even their wives. It’s portable and can fit in a drawer or under the bed. It has security features that trigger an alarm if someone tampers with it. It can be opened using the tag reader or by entering a code using a keypad. Also, an LCD provides a user interface for menu navigation. Options include changing the password, managing RFID tags, and setting the unlock tone.
Key Features and Components:
Microcontroller Chip (ATMega328P): The brain of this project. It has the program code stored in it. It receives/sends signals between other components through the PCB board.
Power Supply: A 3.7V lithium-ion polymer (LiPo) battery combined with a boost module, which steps the voltage up to 5V, which is sufficient to power the microcontroller and peripherals.
Servo Motor: Connected to the lock tongue. Mechanically controls the locking mechanism. It rotates 90 degrees upon receiving signals from the microcontroller to lock or unlock the safe.
Door Sensor: It detects the status of the safe’s door. If the safe is locked and the door is moving, it will send a signal to the microcontroller, and the alarm will be triggered. Also, when the safe door closes, the lock automatically activates, and it prevents the lock from being activated if the door is open.
Card reader (RFID) module: This will give the user the option to open the lock using an authorized RFID card instead of entering a password.
16x2 LCD Display: It will display the lock status and the menu, which will allow the user to choose the option to change the password, or add/remove a tag, and set a tone when the lock opens.
4 x 4 Keypad: This will allow the user to navigate through the menu and enter the password.
Operation Instructions:
First, connect the Smart Safe to a power source using USB-C.
Once powered, the LCD will initialize and prompt the user to enter the default password. Using the keypad, enter the numbers “1234”.
Upon successful entry, a tone will play, and a message will indicate that the safe is unlocked. You will have five seconds to open the safe’s door before it relocks automatically. Open the safe’s door by pulling the handle upward carefully. The door can rotate up to 90 degrees.
 After opening the door, press the “D” key to access the main menu. Navigate through the menu with the buttons “A” to go up, “B” to go down, “C” to select, and “D” to go back.
To change the password, go up to the first option on the menu, then hit “C”. You will be prompted to enter the old password, enter “1234”, then you will be prompted to enter the new password. Enter a four-digit password of your choice, A confirmation message will appear upon success, “Password Changed”.
To add/remove tags, go to the second option on the menu “Add/Remove tags” and hit “C”. You will see two options: “Add tags” and “Remove tags”. Select the first option to add a new tag and hit “C”. You will be prompted to tap the new tag. Grab the tag you want to add and tap it on the safe around one inch below the LCD. A message will appear, “Tag is added.” Hit “D” to go back to the “Add/Remove tags” menu. You can check all registered tags and remove them by selecting the second option, “Remove tags” and hit “C”. A list of all registered tags will be displayed. Navigate to the one you would like to remove and hit the key “C”. You will be prompted to hit the key “C” again if you are sure or you can hit “D” to cancel and go back to the list.
The third option on the main menu is to change the tone that will be played when the lock opens. Select the third option, “Opening tones” then hit “C”. A list of tones will appear, each tone has a name that describes the tone. You can select the tone you like by pushing the key “C”, or you can turn it off by going all the way up to the first option “off” and hitting the button “C”. 
Future Improvements
Possible upgrades include opening the safe via fingerprint. Wi-Fi connectivity for remote monitoring, and a mobile app for access control and notifications.
