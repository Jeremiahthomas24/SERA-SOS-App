# SERA-SOS-App
Smart Emergency Response Assistance    One-tap SOS with location sharing
# 🚨 SERA – Smart Emergency Response Assistance

SERA is a mobile emergency assistance application designed to provide
one-tap SOS alerts with real-time location sharing** to emergency contacts.

## 🔥 Features
- One-tap SOS button
- Live location sharing (every 10 seconds)
- Emergency SMS alerts
- Auto-call sequence (optional)
- Vibration & emergency UI
- Android (Java)

## 🛠 Tech Stack
- Java (Android)
- Android Studio
- Google Fused Location Provider
- SMS Manager API

## 📸 Screenshots

| Home Screen | SOS Triggered |
|------------|--------------|
| (<img width="448" height="842" alt="Screenshot 2026-01-05 151657" src="https://github.com/user-attachments/assets/c5f9882a-8a40-4883-a2c2-143289c76ed5" />
 | (<img width="1919" height="1079" alt="Screenshot 2026-01-05 151615" src="https://github.com/user-attachments/assets/61609070-09c2-4949-95d0-cd2460a059ba" />
 |

## 📱 How It Works
1. User presses SOS button
2. App fetches live GPS location
3. Sends SMS with Google Maps link
4. Shares periodic updates
5. Optional emergency calling

## 📂 Project Structure
- `MainActivity.java` – UI & SOS logic
- `SOSService.java` – Background location service
- `activity_main.xml` – UI layout

## 🚀 Future Enhancements
- Firebase backend
- Live tracking dashboard
- Police & ambulance integration
- iOS version
