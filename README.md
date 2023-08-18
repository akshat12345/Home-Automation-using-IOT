# Home-Automation-using-IOT
This repository contains a demonstration video of a home automation model, in which Raspberry Pi is used for controlling different sensors and pi-cam.
Functionalities-
  1. GUI of the project is developed by using a Python library "tkinter".
  2. Controlling the lights inside the house and the garage door using GUI.
  3. Garage door can also be opened when a person/car is in front of the garage. The weight sensor detects if anything is in front of the door and sends an OTP to the
     registered number. Once the OTP is successfully verified then the door will open automatically.
  4. Home can be put on a secure mode if no one is present inside the house. If any movement is detected at this time it will send a message to the registered number
     like "Intruder in the house".
  5. Then pi-camera is also implemented in this model. Pi-camera serves two functions-
     * It can be turned on by using the GUI.
     * If someone presses the doorbell. Then a live feed link will be sent to the registered number only if the home is not in "secure" mode and gives the option to
       open the door.
Hardware-
  * Raspberry Pi 3 B+
  * Load Cell
  * HX7II (A to D)
  * PIR Sensor
  * Pi Camera
  * Servo motor
