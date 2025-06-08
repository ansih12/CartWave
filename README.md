# CartWave
 CartWave – Smart Cart System for Intelligent Shopping and Checkout Automation
CartWave is a smart shopping cart system developed to modernize the retail shopping experience through automation, personalization, and intelligent design. This system integrates cutting-edge technologies including IoT, Computer Vision, Bluetooth Low Energy (BLE), and mobile applications to provide a seamless shopping journey for customers and operational insights for retailers.

<br>
📌 Features
Automated Product Recognition
Uses computer vision and machine learning (via Teachable Machine) to detect products added to the cart in real time.

BLE-Based Location Detection
BLE beacons placed throughout the store trigger location-specific promotions and services.

Mobile App Integration
Flutter-based app for account linking, cart pairing, purchase tracking, and digital invoices.

Contactless Checkout
Automatically initiates payment when the cart enters a designated payment zone.

Real-Time Inventory Tracking
Inventory is updated instantly as items are added or removed, helping retailers manage stock more efficiently.

Admin Dashboard
Web interface for sales monitoring, inventory control, and managing product data.

<br>
🧠 Technologies Used
Layer	Tools & Technologies
Hardware	Raspberry Pi 4, Pi Camera Module, BLE (ESP32), LCD
Software	Python, Flutter/Dart, Firebase, PHP, HTML/CSS/JS
AI/ML	Teachable Machine for product recognition
Cloud	Firebase Realtime Database & Authentication
IDE/Tools	Arduino IDE, Miro, ClickUp

<br>
📷 System Architecture
The CartWave system is composed of four integrated subsystems:

Raspberry Pi Core Module

Computer Vision System

BLE Location Detection System

Mobile Application

Each component communicates over a secure IoT-based architecture to ensure real-time responsiveness and seamless functionality.

<br>
🚀 Setup Instructions
Clone the Repository

bash
Copy
Edit
git clone https://github.com/yourusername/cartwave.git
cd cartwave
Backend (Firebase)

Configure Firebase for real-time database, authentication, and storage.

Import the provided JSON structure (if any) into Firestore.

Raspberry Pi

Install dependencies using:

bash
Copy
Edit
sudo apt update
sudo apt install python3-pip
pip3 install opencv-python firebase-admin
Connect Pi camera and BLE module.

BLE Setup

Flash ESP32 with provided Arduino code.

Position beacons in relevant store zones.

Mobile App

Install Flutter SDK.

Run app using:

bash
Copy
Edit
flutter run
Admin Dashboard

Host PHP files using Apache/XAMPP or any preferred stack.

<br>
📸 Demo & Screenshots
Include GIFs or screenshots showing:

Product recognition in action

BLE-triggered ads

App-based checkout

Admin dashboard

<br>
📂 Project Structure
markdown
Copy
Edit
cartwave/
├── hardware/
│   ├── raspberry_pi/
│   └── ble_beacons/
├── mobile_app/
│   └── flutter/
├── backend/
│   └── firebase/
├── admin_dashboard/
│   └── php_html_css/
└── docs/
    └── CartWave_Graduation_Report.pdf
<br>
👥 Team
Naif Hamed Dhawi Alghamdi

Anas Hassan Saleh Alghamdi
Supervised by Dr. Naif Abdullah M. Alzahrani

<br>
📜 License
This project is released under the MIT License.

<br>
🌐 Acknowledgements
We thank our advisor, faculty members, and Al-Baha University for their guidance and support throughout this project.









