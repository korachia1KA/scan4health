# 🍎 ScanFood AI

<div align="center">

### 📱 AI-powered food scanning & nutrition assistant

Scan a food product and get useful nutritional information through a simple mobile experience.

**Flutter · Python · OCR · NLP · Firebase · Open Food Facts**

</div>

---

## 🎯 Overview

**ScanFood AI** is a mobile application designed to make food information easier to understand.

The application combines **barcode scanning**, **OCR**, external food databases and AI-oriented processing to identify products and provide nutritional information and a simplified food score.

### Main idea

```
📷 Scan product
      ↓
🔎 Barcode / OCR
      ↓
🌐 Product information
      ↓
🧠 Processing & scoring
      ↓
📱 Nutritional result
```

---

## ✨ Features

- 📦 Barcode-based product lookup
- 📷 OCR fallback for products without a usable barcode
- 🧠 AI/NLP-oriented food information processing
- 🥗 Nutritional information
- ⭐ Simplified food score
- 👤 User profiles
- ☁️ Firebase integration
- 🌍 Open Food Facts integration
- 🇲🇦 Designed with Moroccan products in mind

---

## 🏗️ Architecture

```
Flutter Mobile App
        │
        ├── Barcode Scanner
        │
        ├── OCR
        │
        └── Product UI
              │
              ▼
        Python / AI Layer
              │
              ▼
       Open Food Facts API
              │
              ▼
       Firebase / User Data
```

---

## 🛠️ Technology Stack

| Area | Technologies |
|---|---|
| Mobile | Flutter / Dart |
| AI / Processing | Python · NLP · OCR |
| Product data | Open Food Facts |
| Backend / Cloud | Firebase |
| Version control | Git / GitHub |

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/Zaggardr/ScanFood-Ai.git
cd ScanFood-Ai
```

Install Flutter dependencies:

```bash
flutter pub get
```

Run the application:

```bash
flutter run
```

> Firebase configuration and external API credentials may be required depending on the project configuration.

---

## 🔮 Future Improvements

- 🤖 More advanced food classification
- 🇲🇦 Expanded Moroccan product database
- 📊 Personalized nutrition recommendations
- 🧠 Better OCR and NLP processing
- 📈 Nutrition history and analytics
- 🔔 Personalized food alerts

---

## 👥 Team

Developed as an AI/mobile engineering project by **Driss Zaggar** and collaborators.

---

<div align="center">

### Scan smarter. Understand better. 🥗

</div>
