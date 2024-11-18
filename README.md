# workshop-on-esp8266
none

![image](https://github.com/user-attachments/assets/54300a0c-6645-4721-8caf-d7edb04d8ae0)
Rattle Bots Club Workshop: ESP8266
Welcome to the Rattle Bots Club workshop! This guide will help you get started with the ESP8266 platform by setting up the necessary tools and software.

Workshop Overview
This workshop introduces the ESP8266 platform, a powerful Wi-Fi-enabled microcontroller, perfect for IoT applications. By the end of this session, you'll have the foundational skills to program and use the ESP8266 in your own projects.

Prerequisites
Laptop (one per team of three participants).
Micro USB Cable (compatible with ESP8266 boards).
Pre-installed Arduino IDE (version 1.x or 2.x).
Setting Up ESP8266 in Arduino IDE
Follow these steps to configure your Arduino IDE for ESP8266:

Step 1: Download and Install Arduino IDE
Download the latest version of Arduino IDE for your operating system from the Arduino website.

Step 2: Open Preferences
Launch the Arduino IDE.
Go to File > Preferences (Windows) or Arduino > Preferences (Mac).
Step 3: Add ESP8266 Boards URL
In the Additional Boards Manager URLs field, paste the following link:
bash
Copy code
https://arduino.esp8266.com/stable/package_esp8266com_index.json
You can add multiple URLs by separating them with commas if needed.
Step 4: Install ESP8266 Platform
Open Boards Manager from the Tools > Board menu.
Search for "ESP8266" in the Boards Manager window.
Select and install the esp8266 platform.
Step 5: Select Your ESP8266 Board
After installation, go to Tools > Board, and select the specific ESP8266 board you'll be using (e.g., NodeMCU, Wemos D1 Mini).

Resources
Official ESP8266 Documentation: ESP8266 GitHub
Arduino IDE Troubleshooting: Arduino Help
Support
If you encounter any issues or have questions during the setup, feel free to reach out to the workshop facilitators.

Happy tinkering! 🎉
Rattle Bots Club Team
