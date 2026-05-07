# Modoo-s-Collection
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React Native](https://img.shields.io/badge/React_Native-0.72-020202?logo=react)
![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python)
### Click this image!

[<img src="https://raw.githubusercontent.com/capdale/.github/main/profile/imgs/download.png">](https://drive.usercontent.google.com/download?id=1Se8yGDHNnaCtZJp0zr1arc400_b3aLbm&export=download&authuser=0)

</br>
# Modakbul 🐾

> **Modoo Collection** Project Repository

**Modoo Collection** is a mobile service that recognizes animals through AI, collects them in your personal encyclopedia, and shares discoveries with a community of nature enthusiasts.

---

## 📋 Project Overview

### What is "Modoo Collection"?

**Modoo Collection** (모두의 동물도감, "Everyone's Animal Encyclopedia") is an interactive mobile application that serves as a personalized digital field guide. Users photograph animals with their smartphone camera, and a deep learning model identifies the species. Recognized animals are registered in the user's unique encyclopedia, where detailed information about each species can be explored.

### 🎯 Motivation & Significance

| Existing Solutions | Limitations |
|-------------------|-------------|
| **Google Lens** | Built into most smartphones; shows similar images but lacks precise taxonomic information |
| **Merlin Bird ID** | Excellent for bird identification, but limited to avian species only |
| **Picture Bird** | Specialized in birds; narrow scope of application |

**Modoo Collection** addresses these gaps by:
- ✅ Supporting a **wide range of animal species** (beyond birds) with rich, educational content
- ✅ Adding **gamification elements**: Users actively collect species by taking photos, fostering engagement and curiosity about wildlife
- ✅ Empowering **children and nature observers** to learn about animal taxonomy, characteristics, and habitats while building a community-driven knowledge base

> 🌱 *Our vision: To help users develop ecological awareness and contribute to citizen science through playful, AI-powered exploration.*

---

## 📱 Application Features

### 🔧 System Architecture

The project was developed with clear separation of responsibilities across three core components:
```
┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐
│ Frontend │────▶│ Backend │────▶│ AI Model │
│ (Mobile App) │◀────│ (Server/API) │◀────│ (Deep Learning)│
└─────────────────┘ └─────────────────┘ └─────────────────┘
```



---

### ✨ Key Features

#### 1️⃣ Animal Capture & Recognition 📸
> *"What animal is this?"*

- Point your camera at any animal in your surroundings
- The integrated AI model analyzes the image in real-time and classifies the species
- Instant feedback with confidence scores and alternative suggestions
 

---

#### 2️⃣ Personal Encyclopedia & Detailed Information 📚
> *"Build your own wildlife collection"*

- Successfully identified animals are automatically added to your personal encyclopedia
- Each entry includes:
  - 🧬 Taxonomic classification (Kingdom → Species)
  - 🚨 Conservation status (e.g., Endangered, Least Concern)
  - 📅 Date of first discovery/collection
  - 🌍 Native habitat and distribution map
  - 📝 Fun facts and behavioral insights

> 🎯 *Current scope: 20+ animal species commonly found on campus, with plans for expansion.*
 
---

#### 3️⃣ Community Gallery & Social Sharing 💬
> *"Share your discoveries with the world"*

- Automatic profile creation upon login
- Personal gallery showcasing your collected species and field notes
- Interactive features:
  - ❤️ Like posts from other users
  - 💬 Comment and discuss observations
  - 🔄 Share achievements to social media
 

---

## 🛠️ Tech Stack

| Component | Technologies |
|-----------|-------------|
| **Frontend** | React Native, TypeScript, Redux |
| **Backend** | Node.js, Express, PostgreSQL, Firebase Auth |
| **AI/ML** | PyTorch, MobileNetV3, ONNX Runtime (for mobile inference) |
| **DevOps** | Docker, GitHub Actions, AWS EC2/S3 |

---

## 🚀 Getting Started

### Prerequisites
```bash
- Node.js ≥ 14.x
- Python ≥ 3.8
- Android Studio / Xcode (for mobile builds)
