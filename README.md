# Automatic-Water-Tank-level-with-LCD-display-interface
# REQUIERMENTS
 - ATmega328P microcontroller(__Ardiuno__)
 - Ultasonic sensor HC-SR04
 - 5V Relay, 250v 7A(_As per the Motor current)
 - 3310 Nokia Display
 - LED(_if needed_)
# ABSTRACT
Automatic water level controlling with ATmega328P microcontroller(Ardiuno) with Ultrasonic sensor as a feedback sensor and nokia 3301 display as userfriendly water level display.
# Working
Here,we use ultrasonic sensor for calculate the dept of the water level in the tank Which is connected to the digital pins of Ardiuno 8 (trigger)& 9 (Echo)
As, the level reaches to a threshold level the 5V RELAY triggers to HIGH , This relay is connected to pin 11,as soon as the water level reaches the high level this RELAY goes to LOW.
An, led is connected to the digital Pin 2 which gives a optical feed back to user the state of motor and level of the water
        If the level reaching near the high level, LED STATE IS HIGH__-----
        If the motor is Running ,LED STATE IS BLINKING _-_-_-_-_
This, level and state of water and Motor  is indicated in the in the LCD display respcively.
# Advantages 
_Accurate water level with 1cm of acucuracy.
No need of human effort on controling the motor fully automated.
live Level display in Display
Low cost between (Rs.800).
# Stoppers
_Sometime due to humidity this can affect sensors life.
Long wires are need as per the controllers distance from the tank.
Power cut may be an issue for th working of the setup.
