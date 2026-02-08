# SilentGuard — Intelligent Voice-Triggered Emergency Assistance System
🎓 Graduation Project | Applied AI & System Design

SilentGuard is an intelligent emergency assistance system designed to help users discreetly request help in critical situations where manual interaction with a device may not be possible.

The system listens for a predefined distress keyword chosen by the user. When the keyword is intentionally repeated, SilentGuard activates automatically and sends emergency alerts to selected contacts via the application or SMS, including the user’s live location.

The project focuses on **user safety, reliability, and discretion**, providing a hands-free and fast emergency activation mechanism.

---

## 🚨 Problem Statement
In emergency or high-risk situations, users may not be able to manually interact with their devices to request help. Traditional emergency solutions often require visible actions such as pressing buttons or navigating applications, which may not always be safe or feasible.

SilentGuard addresses this problem by enabling **voice-based emergency activation**, allowing users to discreetly request assistance using a predefined spoken keyword.

---

## 💡 Proposed Solution
SilentGuard operates through a voice-triggered emergency workflow:

1. The user defines a custom distress keyword (e.g., “help”).
2. The system continuously monitors audio input.
3. When the keyword is **intentionally repeated**, the system confirms user intent.
4. Once activated, SilentGuard automatically:
   - Sends emergency notifications via the mobile application and/or SMS
   - Shares the user’s live location with selected emergency contacts

The repetition mechanism acts as a **confirmation strategy** to reduce false activations and ensure intentional triggering.

---

## 🧠 System Overview
SilentGuard consists of the following high-level components:

- **Audio Monitoring Module**  
  Captures environmental audio input from the user’s device.

- **Speech Recognition Component**  
  Converts spoken audio into text using speech-to-text technology.

- **Activation Logic**  
  Detects intentional repetition of the predefined distress keyword.

- **Emergency Alert Module**  
  Sends notifications and SMS messages to trusted contacts.

- **Location Sharing Module**  
  Provides real-time location data to assist contacts in responding quickly.

---

## 🤖 AI Component (Actual Usage)
SilentGuard utilizes **speech-to-text technology** to recognize spoken keywords from audio input.

The intelligence within the system includes:
- Interpreting spoken audio using AI-based speech recognition
- Confirming user intent through controlled repetition
- Automating emergency workflows once activation conditions are met

The activation decision itself is **rule-based**, ensuring predictability and reliability in safety-critical scenarios.

---

## 🛠️ Technologies Used
- Speech-to-Text / Voice Recognition
- Audio Signal Processing
- Mobile Application Development
- Backend Services
- SMS & Notification Services
- Location Services (Live Location Sharing)

---

## ⭐ Key Features
- Voice-triggered emergency activation
- Customizable distress keyword
- Reduced false activations through repetition confirmation
- Automated alerts via application and SMS
- Live location sharing with trusted contacts
- Designed for discreet and hands-free usage

---

## 👩‍💻 My Contributions
- Designed the overall system workflow and emergency activation logic
- Integrated speech recognition for voice-triggered activation
- Implemented the alerting and live location sharing mechanisms
- Contributed to system testing, validation, and documentation

---

## 🔒 Code Availability
The full implementation is not publicly available to protect the originality and security aspects of the graduation project.

System design, functionality, and outcomes are documented in this repository.  
The implementation can be discussed during interviews if required.

---

## 📄 Academic Context
This project was developed as a graduation requirement.  
Full academic documentation is available upon request.

---

## 📎 Repository Purpose
This repository serves to:
- Present the project concept and system design
- Demonstrate applied AI usage in a real-world safety scenario
- Showcase system thinking, problem-solving skills, and engineering decisions
