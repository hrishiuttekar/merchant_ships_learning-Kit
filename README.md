📖 README Intro
🚢 Merchant Ship IoT – Hackathon Project

This project simulates a smart Merchant Ship that can monitor, detect, and control critical functions in real-time using IoT technology.
Designed and developed for a student hackathon, it demonstrates how sensors + web technology + automation can make shipping safer and more efficient.

✨ Features

🔥 Engine Room Monitoring: Temperature & Humidity (DHT11).

🛢 Oil Tank Level: Moisture sensor with low fuel alerts.

☠️ Gas Detection: MQ135 sensor with safety threshold.

🌊 Radar System: Ultrasonic sensor sweeping via servo (0–180°) to detect obstacles.

📡 GPS Tracking: Live latitude, longitude, satellites, and time.

⚖️ Ship Balance: MPU6050 motion sensor (roll, pitch, yaw).

💡 Visual Alerts: NeoPixel LEDs (green = safe, red = alert).

🔔 Audible Alerts: Buzzer for emergencies.

🏗 Crane Simulation: Two servo cranes for cargo loading/unloading.

📺 Dual OLED Displays: One for engine/oil/alerts, another for GPS/environment.

🌐 Web Dashboard:

Live sensor data and radar visualization.

Crane and radar control via buttons/sliders.

Real-time updates using Server-Sent Events (SSE).

🛠 Tech Stack

Hardware: ESP32, DHT11, MQ135, Ultrasonic Sensor, MPU6050, GPS Module, OLED Displays, Servos, NeoPixel, Buzzer.

Software: Arduino IDE, C++ (ESP32), LittleFS, WebServer, ArduinoJson, TinyGPSPlus, ESP32Servo.

Web: HTML, CSS, JavaScript (dashboard served from ESP32).

🚀 How It Works

Sensors continuously collect data (engine, outer environment, gas, oil, GPS, radar).

ESP32 processes and displays values on OLED screens.

Alerts trigger NeoPixel lights and buzzer if unsafe conditions are detected.

A Wi-Fi web dashboard allows monitoring + controlling cranes and radar in real-time.

Data is shared via JSON APIs and SSE for live updates.

⚓ This project shows how IoT can make maritime operations safer, smarter, and more efficient.
