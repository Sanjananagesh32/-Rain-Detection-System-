# -Rain-Detection-System-
Using ESP32 DEVKit V1 a Rain Detection System. was deployed  using Arduino software and CPP programming language.
The system detects rainfall through a rain sensor module, and upon detection, activates a buzzer to alert nearby users. This project aims to provide a cost-effective, scalable solution for smart rain monitoring.

Features
- Detects rain in real-time using a rain sensor.
- Triggers a buzzer when rain is detected.
- Built using ESP32 and C++.
- Easily deployable using Arduino IDE.
- Future scope: Notification support via Telegram bot.

Hardware Components
- ESP32 DevKit V1
- Rain Sensor Module (YL-83 / FC-37)
- Buzzer
- Jumper wires
- Breadboard or custom PCB

Software and Tools
- Arduino IDE
- C++ (Arduino-style)
- ESP32 Board Manager installed in Arduino
- Telegram Bot API (for future updates)

Working Principle
1. The rain sensor detects water droplets.
2. If rain is detected (analog/digital signal threshold), the ESP32 triggers a digital output.
3. This output drives a buzzer to alert the presence of rain.
4. (Future scope) A Telegram Bot sends a notification to the user’s smartphone.

Installation

1. Set up the Arduino IDE  
   - Install the ESP32 board in Arduino IDE.  
   - Connect your ESP32 board via USB.
    
2. Circuit Setup 
   - Connect the rain sensor output to a GPIO pin on the ESP32.
   - Connect the buzzer to another GPIO pin with proper current-limiting resistor.
   - Power everything through USB or external 3.3V/5V source.
     
3.  Load the Code and run
   - Open the .ino file from this repository.
   - Select the correct board and port.
   - Upload the code to the ESP32.
   - after connection is established the serial monitor/ rain sensor dectects rain the buzzer is turned on   

   
