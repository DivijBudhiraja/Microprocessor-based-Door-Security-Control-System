# Microprocessor-based-Door-Security-Control-System

The aim of our project is to design and implement a door security system using
8086 microcontroller which will help solve the issues like forgetting to close the
doors or locking them, unauthorized access to the building or house. We will
use EMU8086 to implement the project.
The door will open when the user enters the authorized password. Any
unauthorized person attempting to gain access to the house or building protected
by the door will cause the alarm to sound. The alarm will only stop when the
user with the master password will enter the alarm code. 

This system controls the opening and closing of a door based on password
entry. If the password is correct the person can enter. Each person is given two
chances to enter the correct password. On failure an alarm is sounded. Inside the
room a button is available when the button is pressed the door opens for 1 Min,
so that the person can leave the room.

The system will consist of three modes: -

• User mode- The user will be able to open the door using the user
password. If the first password attempt fails, the user will be given a
second attempt failing which will cause an alarm to go on.

• Admin mode- The administrator will be able to change the user
password by using the admin password. The admin is only allowed one
attempt failing which will cause the alarm to go off.

• Alarm mode- When the alarm is sounded, to turn it off an alarm code
needs to be entered on the system.

![image](https://user-images.githubusercontent.com/70505625/169842672-e0b30697-5f42-4e78-96e1-409b49c690ef.png)


![image](https://user-images.githubusercontent.com/70505625/169842581-0585cca2-a993-4e2a-9595-e9ed59fffc95.png)
