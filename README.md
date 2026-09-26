# 🚗 UrbanMove
### Smart Travel. Safer Cities.

![GitHub Pages](https://img.shields.io/badge/deployed-GitHub%20Pages-blue)
![Status](https://img.shields.io/badge/status-prototype-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Made with](https://img.shields.io/badge/Made%20with-HTML%2FCSS%2FJS-yellow)

**UrbanMove** is a smart urban mobility prototype designed to make city travel safer, more accessible, and efficient for everyone. It combines real-time transit updates, smart routing, accessibility preferences, and emergency support into a single, user-friendly mobile-first interface. 

🔗 **Live Demo:** [https://your-username.github.io/urbanmove/](https://your-username.github.io/urbanmove/) *(Replace `your-username` with your actual GitHub username)*

---

## 🌟 The Vision

> *"Real-time updates, smart routes, and travel made for everyone."*

Navigating a busy city like Karachi can be chaotic. UrbanMove solves this by prioritizing:
- **Smart Routes:** Choosing the best way based on time, cost, and transfers.
- **Real-Time Updates:** Staying informed about traffic, delays, and route changes.
- **Accessibility First:** Ensuring travel is possible for everyone, everywhere.
- **Emergency Support:** Help is just one tap away when you need it.

---

## ✨ Key Features (Based on Prototype)

### 1. Onboarding & Home Dashboard
- 🌅 **Personalized Greeting:** "Good morning, Ahmed" with quick access to frequent trips (Home > University, Home > Office).
- ⚡ **Quick Access Menu:** Transport, Routes, Parking, and SOS at your fingertips.
- 📡 **Live Updates:** Real-time traffic disruption alerts (e.g., "No major disruptions").

### 2. Smart Routing & Comparison
- 🔍 **Search & Recent Places:** Quickly find University, City Hospital, Lucky One Mall, or the Airport.
- ⚖️ **Compare Routes:** Filter by Fastest, Cheapest, Least Walk, Reliable, or Fewest Transfers.
- 🚌 **Multi-Modal Transport:** Compare Bus #12 (Cheapest: Rs. 80, 1h 20m), Metro + Bus (Best Balance: Rs. 120, 55 min), Ride (Careem - Fastest: Rs. 550, 40 min), and Private Car (50 min).

### 3. Live Journey & Navigation
- 🗺️ **Live Tracking:** Map view with ETA and transit timeline (Home 7:30 AM → Main Road 7:55 AM → University 8:45 AM).
- ⚠️ **Traffic Alerts:** Real-time accident detection and alternative route suggestions (e.g., "Route Updated: A faster route is now available!").
- 🧭 **Turn-by-Turn Navigation:** Dark mode map with clear directional cues (e.g., "Continue straight for 750m").

### 4. Accessibility & Inclusivity
- ♿ **Custom Preferences:** Toggle settings for Wheelchair accessible, Avoid stairs, Elevator available, Fewer transfers, Nearby seating, and Accessible toilets.

### 5. Smart Parking & Emergency
- 🅿️ **Smart Parking:** Real-time space availability, distance, and hourly rates (Parking B: Rs. 150/hr, Parking C: Rs. 120/hr, Parking D: Rs. 100/hr).
- 🚨 **SOS Emergency:** Quick access to Ambulance, Police, Hospital, Emergency Contacts, and "Share My Location" feature.

### 6. Offline Mode & Settings
- 📶 **Offline Mode:** View saved places and maps without an internet connection.
- ⚙️ **Settings:** Profile management (Ahmed), Language, Location Access, Transport Preferences, Privacy & Data, Notifications, and Saved Trips.

---

## 🖥️ Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript 
- **Icons/UI:** Font Awesome / Custom SVG icons
- **Hosting:** GitHub Pages (Static)
- **Design Aesthetic:** Modern, clean mobile-first UI with a dark mode map interface.

---

## 📁 Project Structure

Ensure your project folder looks like this before deploying:

```text
urbanmove/
├── index.html          # Main entry point (Landing + Onboarding)
├── css/
│   └── styles.css      # Custom styling (Mobile-first, responsive)
├── js/
│   └── script.js       # Interactive logic (Tabs, map mockup, toggles)
├── assets/
│   ├── images/         # Icons, background patterns, and screenshots
│   └── maps/           # Offline map tiles or static images
└── README.md
