# Nyinauni - AI-Powered English Learning Platform

Nyinauni is a high-fidelity, production-ready English learning platform designed to provide a personalized and immersive educational experience. Built with a focus on modern aesthetics and seamless user workflows, the platform guides students from initial onboarding through a tailored learning journey.

---

## 🚀 Key Features

### 1. **Bespoke Onboarding Experience**
- **Personalization Survey**: A high-fidelity, 5-step survey that captures user goals, skill levels, and learning preferences.
- **Dynamic Visuals**: Adaptive imagery and motivational quotes that respond to user inputs in real-time.
- **State Persistence**: Uses `localStorage` to ensure users pick up exactly where they left off.

### 2. **Advanced Authentication Portal**
- **Dual-Auth System**: Supports both standard Email/Password authentication and one-click Google Sign-In.
- **Split-Screen UI**: Trendy design with high-quality motivational imagery paired with a minimalist form interface.
- **Firebase Integrated**: Fully powered by Firebase Auth for secure, production-grade session management.

### 3. **High-Fidelity Study Dashboard**
- **Bento-Style Architecture**: A modern, card-based layout for quick access to lessons, progress, and exploration.
- **Learning Map**: Interactive subject tree that visualizes the student's educational path.
- **Real-time Analytics**: Visualized statistics and progress tracking to keep students motivated.
- **Mentor Management**: Integrated interface for following and interacting with language mentors.

---

## 🛠️ Technology Stack

- **Frontend**: Vanilla HTML5, CSS3 (Modern Flexbox/Grid), JavaScript (ES6+).
- **Backend/Auth**: Firebase (Modular SDK v10).
- **Typography**: Poppins (Google Fonts) for a clean, professional feel.
- **Design System**: Custom CSS variables for a consistent primary-yellow and dark-navy aesthetic.

---

## 📂 Project Structure

```text
englishtutor/
├── index.html          # Landing Page & Global Auth Entry
├── auth.html           # Unified Sign-In / Sign-Up Portal
├── survey.html         # Personalization & Onboarding Flow
├── dashboard.html      # High-Fidelity LMS Dashboard
├── study.html          # Alternative Bento-Style Dashboard
├── assets/             # Image and Vector Assets
└── README.md           # Project Documentation
```

---

## 🔧 Installation & Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/nyinauni.git
   ```

2. **Configure Firebase**:
   - Update the `firebaseConfig` object in `index.html`, `auth.html`, `survey.html`, and `dashboard.html` with your own credentials from the [Firebase Console](https://console.firebase.google.com/).

3. **Run Locally**:
   - Simply open `index.html` in your browser or use a local live server (e.g., Live Server extension in VS Code).

---

## 🎨 Design Philosophy

Nyinauni follows a **"Premium Educational"** aesthetic:
- **Primary Color**: `#faff54` (Energetic Yellow)
- **Secondary Color**: `#42C2FF` (Trustworthy Blue)
- **Base**: `#111827` (Deep Professional Navy)
- **Typography**: Focus on readability and hierarchy using various weights of the Poppins font family.

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

*Built with ❤️ for English Learners everywhere.*
