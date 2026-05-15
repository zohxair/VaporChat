# 🌌 VaporChat

VaporChat is a high-performance, single-page real-time messaging application featuring a "Midnight Neon" aesthetic. It leverages Firebase for backend services (Firestore/Auth) and connects to the DeepSeek-V4-Pro model via the Hugging Face Router for integrated AI assistant features.

## ✨ Features
- **Real-Time Messaging:** Instant data synchronization using Firestore `onSnapshot`.
- **Google Authentication:** Secure login integration via Firebase Auth.
- **AI Integration:** Integrated `/ask` command powered by the **DeepSeek-V4-Pro** model.
- **Midnight Neon UI:** Responsive, vaporwave-inspired design using Tailwind CSS with glassmorphism and neon accents.
- **Serverless Hosting:** Optimized for deployment on GitHub Pages.

## 🛠️ Tech Stack
- **Frontend:** HTML5, Tailwind CSS, JavaScript (ES6+)
- **Backend-as-a-Service:** Firebase (Auth & Cloud Firestore)
- **AI Engine:** DeepSeek-V4-Pro (via Hugging Face Inference API)

## 🚀 Getting Started
1. **Host:** Upload `index.html` to a GitHub repository and enable GitHub Pages.
2. **Authorize:** Add your GitHub Pages URL to the "Authorized Domains" in your Firebase Auth settings.
3. **Configure:** Open the app, click the **Settings ⚙️** icon, and enter your Hugging Face API Token.
4. **Chat:** Sign in with Google and use `/ask` to chat with the AI.

## 📜 Computer Science Context (9618 Syllabus)
This project demonstrates key practical applications of:
- **Client-Server Architecture:** Managing state between the browser and cloud databases.
- **API Integration:** Implementing RESTful-style communication with external LLM providers.
- **Asynchronous Programming:** Handling promises and async/await for smooth UI updates.
- **Data Security:** Using `localStorage` for client-side key management.
