# 🚨 SERA – Smart Emergency Response Assistance

SERA is an Android-based emergency response application designed to provide **instant SOS communication** during critical situations. With a single tap, users can notify emergency contacts, share their location, and alert a server for further action.

---

## 🧩 Problem Statement

During emergencies, victims often fail to:
- Make quick phone calls
- Share accurate location
- Alert multiple people at once

Delays in communication can cost lives.

---

## 💡 Solution

SERA solves this problem by providing:
- **One-tap SOS activation**
- **Automatic SMS alerts** to emergency contacts
- **Instant phone call** to a priority contact
- **Location sharing** using GPS
- **Server-based SOS logging** for scalability

---

## ⚙️ Features

- 📲 Send SOS message to multiple contacts
- 📞 Auto-call emergency contact
- 📍 Fetch and send last known GPS location
- 🌐 Send SOS data to backend server (Node.js)
- 🔐 Runtime permission handling
- 🛑 Fallback handling if permissions or GPS are unavailable

---

## 🛠 Tech Stack

### Android App
- Java
- Android Studio
- Google Play Services Location API
- Volley (Networking)

### Backend (Optional)
- Node.js
- Express.js
- REST API

---

## 📸 Screenshots

| Home Screen | SOS Triggered |
|------------|--------------|
| ![Home](screenshots/home_screen.png) | ![SOS](screenshots/sos_pressed.png) |

---

## 🧪 How It Works

1. User presses **SOS**
2. App requests permissions (SMS, Call, Location)
3. Sends emergency SMS to all contacts
4. Initiates phone call to primary contact
5. Captures last known GPS location
6. Sends SOS data to server

---

## 🚀 How to Run the App

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/SERA-Smart-Emergency-Response.git
