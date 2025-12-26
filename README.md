# DRONE
Offline tactical voice navigation for GPS-denied battlefields
Dismounted Resilient Offline Navigation Interface  

Voice-guided tactical navigation for soldiers — 100% offline, zero GPS dependency, built for ₹10,000. 

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)]()
[![Raspberry Pi](https://img.shields.io/badge/Hardware-RPi_Zero_2_W-orange)]()
[![Offline](https://img.shields.io/badge/Status-100%25_Offline-red)]()


 Overview  
DRONI is a soldier-first navigation assistant designed for GPS-denied battlefields — where jamming, terrain, or electronic warfare render conventional systems useless. Unlike civilian apps that fail without satellite signals, DRONI uses pre-loaded terrain maps, inertial dead reckoning, and tactical path logic to deliver spoken, turn-by-turn guidance through covered routes — even in complete signal blackout.

Built for Siachen, LoC, and Northeast jungle operations, DRONI prioritizes **survivability over speed, guiding troops through ravines and tree lines while avoiding open, high-risk zones.

No internet. No cloud. No compromise on operational security.


 Key Features  
| Feature | Description |
|--------|-------------|
| ✅ 100% Offline | Zero network dependency — works in deep valleys or urban canyons |
| 🗣️ Voice Guidance | Real-time spoken directions via offline TTS (`pyttsx3`) |
| 📡 GPS-Denied Navigation | Switches to step-count + compass-based dead reckoning when GPS fails |
| 🛡️ Tactical Routing | Avoids exposed areas; favors concealment and cover |
| 🔋 Portable & Low-Cost | Runs on Raspberry Pi Zero 2 W (< ₹10,000 total) |
| 🎧 Bluetooth Ready* | Pairs with bone conduction headsets for covert audio |



Tech Stack  
- Language: Python 3.9+  
- Maps: OpenStreetMap (processed via `osmnx`)  
- Routing: Risk-weighted Dijkstra (`networkx`)  
- Voice: `pyttsx3` (offline text-to-speech)  
- Sensors: GY-91 (MPU6050 + HMC5883L) for step & heading  
- OS: Raspberry Pi OS Lite (headless)  


