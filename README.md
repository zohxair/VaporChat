# 🌌 VaporChat: AI-Integrated Messaging Protocol

VaporChat is a high-performance, single-page communication interface built with a "Midnight Neon" aesthetic. It features real-time data synchronization via Firebase and an integrated AI assistant powered by the DeepSeek-V4-Pro model.

## ✨ Core Features
- **Direct Email Messaging:** Initiate secure communication links with any user via their email address.
- **DeepSeek AI Integration:** Use the `/ask` command to query the DeepSeek-V4-Pro model via the Hugging Face Router.
- **Real-Time Synchronicity:** Instant message delivery and receipt powered by Firestore `onSnapshot` listeners.
- **Google OAuth 2.0:** Secure, environment-aware authentication protocol.
- **VaporWave UI:** A custom-engineered "Midnight Neon" interface featuring glassmorphism, responsive CSS grids, and CSS3 animations.

## 🛠️ Technical Stack
- **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6+)
- **Backend:** Firebase (Authentication & Cloud Firestore)
- **AI Engine:** DeepSeek-V4-Pro (via Hugging Face Inference API)
- **Architecture:** Client-Server model with asynchronous API handling.

## 🚀 Deployment & Setup
1. **Hosting:** Deploy to a secure `https` environment (e.g., GitHub Pages) to enable OAuth features.
2. **Firebase Configuration:** - Add your deployment URL to **Authorized Domains** in the Firebase Console.
   - Ensure Firestore rules allow read/write access for authenticated users.
3. **AI Activation:** - Open **System Settings** in the VaporChat sidebar.
   - Enter your `HF_TOKEN` (VaporKey) to enable the AI protocol.

## 📜 Computer Science Context (9618 Syllabus)
This project serves as a practical implementation of several A-Level Computer Science concepts:
- **Client-Server Model:** Managing state and data persistence across distributed nodes.
- **API Connectivity:** Implementing REST-style requests with Authorization headers for LLM inference.
- **Data Security:** Client-side encryption of API tokens using `localStorage`.
- **Robustness:** Implementation of `try-catch` blocks and protocol-aware error handling to prevent runtime crashes.
