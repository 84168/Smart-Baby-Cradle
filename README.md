Smart Baby Cradle 👶🛏️

Smart Baby Cradle is an IoT-powered solution designed to help parents soothe their infants with minimal intervention. It combines sound detection, automated motion, and mobile notifications to create a responsive and comforting environment for babies.

🧠 Features

Cry Detection: Uses a sound sensor to detect when the baby is crying.
Real-Time Alerts: Sends instant notifications to the parent's mobile app.
Auto-Swing Mechanism: Activates cradle swinging until the baby stops crying.
Hands-Free Comfort: Reduces the need for constant manual monitoring.

🛠️ Hardware Components

Component	Description

ESP32:	Microcontroller with Wi-Fi capability

Sound Sensor (Analog):	Detects crying based on sound threshold

Servo Motor: Controls cradle swing

Wi-Fi Network	Required for Blynk connectivity

Mobile Device	Runs Blynk app for notifications/control

🔧 Setup Instructions

Connect Hardware:

Sound sensor to analog pin GPIO 34

Servo motor to digital pin GPIO 2

Upload Code:

Use Arduino IDE with required libraries (ESP32Servo, BlynkSimpleEsp32)

Configure Blynk:

Use Blynk 2.0 template ID, name, and auth token

Set up virtual pins:

v1: Sound value display

V2: Cry alert message

V3: Servo position control

Power On:

Connect ESP32 to Wi-Fi

Monitor serial output and app notifications

📱 Mobile App Integration

Download the Blynk IoT app

Create a project using the provided template ID and auth token

Add widgets:

Gauge for V1

Notification for V2

Slider for V3 (0–180 degrees)
