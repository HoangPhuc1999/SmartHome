
# ABOUT THIS PROJECT


Hello everyone, my name is Phuc Hoang Nguyen, student of Computer Engineering Technology from Humber College.<br>
If you want to build a project to control 28BYJ-48 Stepper Motor with ULN2003APG driver, this is a step by step blog to help you achieve that.

<img src ="Documentation/Project picture/pcb_complete.jpg" alt="image of connected hcr-s04"><br>



# COMPONENTS AND SUPPLIES

28BYJ-48 Stepper Motor<br>

<img src ="Documentation/Stepper_Motor_obl_600__73570.1448057593.1280.1280.png" alt="image of connected hcr-s04"><br>

ULN2003APG Driver<br>

<img src ="Documentation/Driver board ULN2003 -550x550.jpg" alt="image of connected hcr-s04"><br>

It is better to buy the whole arduino kit on amazon, as the kit will have all the component needed for the project, this include:<br>

+) uln2003APG<br>
+) 28BYJ-48 stepper Motor<br>
+) Arduino <br>
+) Beard board<br>
+) Wire<br>
+) Jumper Wire<br>

Link to buy the arduino kit :(https://www.amazon.ca/Elegoo-Project-Starter-Tutorial-Arduino/dp/B01D8KOZF4/ref=sr_1_1_sspa?crid=2DVN7H6ZQLWPG&keywords=arduino+kit&qid=1574921884&sprefix=arduino+k%2Caps%2C145&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExTUVOUEhHNEhDTUZQJmVuY3J5cHRlZElkPUEwOTc2NjcxQVRIUzQyVFBNQUg3JmVuY3J5cHRlZEFkSWQ9QTA3NjA2NDQxMFhPMlJCUkVSSlRJJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)

So instead of waiting months for your components to arrive if you purchase through China company, the shipping time will aproximately 2 bussiness days through amazon. 

# SOFTWARE

https://www.arduino.cc/en/Main/Software

# NECESSARY TOOLS AND MACHINES

Soldering iron gun<br>

<img src ="Documentation/Project picture/solder.jpg" >


# Wiring - Connecting the Driver with the Arduino and the motor 

The wiring diagram/schematic below shows you how to connect the ULN2003 driver board to the 28BYJ-48 stepper motor and the Arduino.

<img src ="Documentation/Project picture/Phuc_bb1.jpg" >
Documentation/Project picture/beard board.jpg
<img src ="Documentation/Project picture/beard board.jpg">

I use jumper wire with different color to make the connect as the picture above.

# ULN2003 and 28BYJ-48 to Arduino Connections

| ULN2003APG    | Connection     |
| ------------- | -------------  |
| IN1           | Pin 11 Arduino |
| IN2           | Pin  9 Arduino |
| IN3           | Pin 10 Arduino |
| IN4           | Pin  8 Arduino |
| -             | Ground Arduino |
| +             | 5V Arudino     |
 

