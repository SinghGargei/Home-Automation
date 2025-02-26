# 🏡 Home Automation with ESP8266 & Blynk

🚀 This Home Automation System allows you to control appliances like a Fan and LED remotely using the Blynk App and an ESP8266 NodeMCU.

## 📌 Features

✔ Wi-Fi Controlled: Operate appliances over the internet.

✔ Blynk App Integration: Mobile-based control.

✔ Fan & LED Control: Turn ON/OFF appliances remotely.

✔ Real-time Serial Monitoring: Debugging made easy.

✔ Scalable System: Add more devices effortlessly.

## 🛠️ Components Used

ESP8266 NodeMCU – Wi-Fi microcontroller for control.

LED – Indicator light.

Fan (or any appliance) – Controllable via relay.

Relay Module – Required for high-power appliances.

Jumper Wires – For necessary connections.

## 📡 Circuit Diagram



![Circuit Diagram](![WhatsApp Image 2024-09-11 at 23 05 36_5e9537d1](https://github.com/user-attachments/assets/3e4e4d0c-b5f0-46c4-8bff-9fdfcab35b68)
)


## 🚀 Getting Started
### 🔹 1️⃣ Install Required Libraries
Ensure you have the following libraries installed in Arduino IDE:
✅ Blynk (BlynkSimpleEsp8266.h)
✅ ESP8266WiFi (ESP8266WiFi.h)

### 🔹 2️⃣ Set Up Blynk App
1️⃣ Download the Blynk App on Android/iOS.
2️⃣ Create a new project and copy the Blynk Auth Token.
3️⃣ Add two buttons:

V0 → Fan
V1 → LED
### 🔹 3️⃣ Upload Code to ESP8266
1️⃣ Open Arduino IDE.
2️⃣ Enter your Wi-Fi credentials in the code.
3️⃣ Paste your Blynk Auth Token.
4️⃣ Upload the code and open Serial Monitor.
