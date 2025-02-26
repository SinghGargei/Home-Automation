🏡 Home Automation using ESP8266 & Blynk
![image](https://github.com/user-attachments/assets/6500e721-99d9-465a-b132-88532b8ce5b1)


🚀 This Home Automation System allows you to control appliances like a Fan and LED remotely using the Blynk App and an ESP8266 NodeMCU.

🌟 Features
✅ Wi-Fi Controlled: Uses ESP8266 to connect to the internet.
✅ Blynk App Integration: Mobile-based control for easy access.
✅ Fan & LED Control: Turn ON/OFF appliances from anywhere.
✅ Serial Monitoring: Real-time status updates for debugging.
✅ Scalable: Can add more devices easily.

🛠️ Components Required
ESP8266 NodeMCU (1x) – Wi-Fi microcontroller to control appliances.
LED (1x) – To indicate system status.
Fan (or any appliance) (1x) – Can be replaced with any AC/DC appliance.
Relay Module (optional) – If controlling high-power devices.
Jumper Wires – For necessary connections.
🔧 Circuit Diagram
(You can add a circuit diagram here for better clarity.)

🚀 Getting Started
1️⃣ Install Required Libraries
Make sure you have the following libraries installed in the Arduino IDE:

Blynk (BlynkSimpleEsp8266.h)
ESP8266WiFi (ESP8266WiFi.h)
2️⃣ Set Up Blynk App
Download the Blynk App (Available on Android & iOS).
Create a new project and get the Blynk Auth Token.
Add two buttons:
V0 for the Fan
V1 for the LED
3️⃣ Upload Code to ESP8266
Open Arduino IDE.
Enter your Wi-Fi credentials in the code.
Paste your Blynk Auth Token.
Upload the code and open Serial Monitor.
