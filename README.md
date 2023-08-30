# Anti-Sleep-Alarm-for-Cars
#### Task:- Creating an anti-sleep alarm for vehicles that will wake up drivers if they fall asleep while driving.

### List of Components:-
1. Arduino Uno
2. DC Gear Motor
3. Piezo Buzzer
4. Single Channel Relay Module
5. Eye Blink Sensor
6. Breadboard

### Model Description:-
1. The Anti Sleep Alarm consists of an Arduino Uno microcontroller connected to the Relay Module which is connected to the DC Gear Motor.
2. An Eye Blink Sensor is connected which is used to sense the eye movements and gives an indication as to whether the driver is asleep or awake.
3. A Piezo Buzzer is connected to alert the driver if they have gone to sleep to wake them.

![image](https://github.com/Sghosh32/Anti-Sleep-Alarm-for-Cars/assets/89793505/96981eb3-ffb7-4719-953c-6f5881ca4610)
#### Circuit Diagram

![image](https://github.com/Sghosh32/Anti-Sleep-Alarm-for-Cars/assets/89793505/71296f6b-e6e4-48d1-be16-4ac0f58fb6c5)
#### Schematic Diagram

### Model Working:-
1. Supply is given to Arduino Uno through a USB cable.
2. When the driver is in normal/awake condition when the driver blinks normally, the condition is assumed that a normal human eye blink takes around 50ms to blink. Hence, a normal eye blink would not trigger the piezo buzzer.
3. When the driver falls asleep, a buffer of 3 seconds is given after which the piezo buzzer is triggered to alert the driver.
4. If the driver does not wake 3 sec after the buzzer has been activated, then the relay module cuts the supply to the DC Gear Motor, which will make the car come to a complete stop.

### Video Demonstration:-
https://drive.google.com/file/d/1cJU4zMomiRAbtyzpj1tAVndCHbhdYe_k/view?usp=sharing 
