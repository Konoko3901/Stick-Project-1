# Stick-Project-1

This project is an open exploration into making my own joysticks for PC gaming.  The end goal is to have a 3 axis dual stick and split dual throttle setup, to document the journey, and have directions for replicating the end product.  Any ideas conveyed within this project will attempt to explain things assuming that the audience has zero working knowledge or experience with electronics, mechanics, coding, or engineering.  For those of you that do, cool, please bear with me as I don't want to miss or overlook anything that someone may find important.  After watching several video's on the various subjects below some points were glossed over or flat out not discussed.  I am attempting to put everything someone needs to build this from scratch into one spot while making it easy to navigate so you can grab the chunk of info you need to finish or repair your project.  There will be tool and parts lists with each section, hopefully I'll be able to reate actual IPB's (Illistrated parts breakdown) of each assembly and include those with hyperlinks to the 3d printer files, if applicable to the part.  

General overall (mostly) video of a DIY control stick build
https://www.youtube.com/watch?v=Y9wrDS_DBf4

# Stick Gimbal
  Open source content creator https://github.com/bhowiebkr/open-joystick will be a starting point for gimbal design ideas

# Stick Mounting Housing

# Stick Micro-controller
  The microcontroller for this project in an Arduino Pro-Micro type controller, mine aren't from Arduino but they do have the ATMega 32u4 chip.  As one requirement of the project is to have USB communication to the PC and the 32u4 has that built in. So with one hardware choice we avoid needing additional hardware and additional code to do the same thing
  Arduino Pro-Micro type micro-controller basic code.  
  https://www.arduino.cc/reference/en/libraries/joystick/
  https://github.com/MHeironimus/ArduinoJoystickLibrary
  https://www.youtube.com/watch?v=hoCOq9Ngp44&t=592s
  

# Stick Stick

# Throttle Housing

# Throttle Stick
  Going for a split thottle to accomidate multi-engine aircraft or anything else a pilot may need an extra throttle axis for.  The throttle is going to have several buttons, hat switches, and hopefully at least one thumb stick for controlling freelook, targeting pods, etc.  

# Throttle Friction Joint

# Throttle Micro-controller

# Resurecting Old Sticks

Old stick is a Saitek ST220, I had to replace the internal board with an Arduino Pro-Micro type micro controller in order to make the stick work on modern PC's.  After I removed the old board I looked at the wiring to figure out which wires were ground, 5v, and signal.  I pinned the wire's using a kit I cannot rememeber the name of (Replace next week).  Then attached the wires to the corresponding spots on the Pro-Micro, plugged it in and it's back up and running.

Old stick number two is a Saitek Pacific aviator for PS3.  Going to be replacing the internal board with another micro pro.
