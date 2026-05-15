<<<<<<< HEAD
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
=======
# 🩺 MediAI
### AI-Powered Medical Assistant (React + Gemini API)

---

## 🔗 Repository Link
👉 https://github.com/PranshuGupta28/MediAI

---

## 📌 Project Overview
MediAI is an AI-based medical chatbot that provides **professional healthcare responses** using the Gemini API.

The system is designed with strict prompt engineering to ensure:
- ✅ Only medical-related queries are answered  
- ❌ Non-medical queries are restricted  
- 🧠 Responses are safe and professional  

---

## ✨ Features

### 🧠 AI Medical Assistant
- Powered by Gemini API  
- Generates structured responses  

### 🎯 Smart Query Filtering
- Accepts only healthcare-related queries  
- Prevents irrelevant prompts  

### 💬 Interactive UI
- Chat-based interface  
- Clean and simple design  

### ⚡ Fast Performance
- Built with React + Vite  
- Optimized for speed  

### 🔒 Safety Focus
- Avoids harmful outputs  
- Maintains professional tone  

---

## 🛠️ Tech Stack

- ⚛️ React.js  
- ⚡ Vite  
- 🤖 Gemini API  
- 🎨 CSS  

---

## 📂 Project Structure

```bash
AAROGYA-AI/
│── public/
│── src/
│   ├── assets/
│   ├── components/
│   │   ├── Main/
│   │   │   ├── Main.jsx
│   │   │   ├── Main.css
│   │   ├── Sidebar/
│   │   │   ├── Sidebar.jsx
│   │   │   ├── Sidebar.css
│   │
│   ├── config/
│   │   └── MediAI.js
│   │
│   ├── conf/
│   │   └── conf.js
│   │
│   ├── context/
│   │   └── Context.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│
│── .env
│── index.html
│── package.json
│── vite.config.js
│── README.md
```





## ⚙️ Setup & Installation

### 1️⃣ Clone Repository

git clone https://github.com/PranshuGupta28/MediAI.git
```bash
cd MediAI
```

2️⃣ Install Dependencies
```bash
npm install
```
3️⃣ Setup Environment Variables

Create a .env file in the root directory:
```bash
VITE_GEMINI_API_KEY=your_api_key_here
```
4️⃣ Run Project
```bash
npm run dev
```


🧠 How It Works

User enters a query

System checks if the query is medical-related

If valid → request is sent to Gemini API

AI processes and generates response

Response is displayed in the UI

⚠️ Disclaimer

This project is for educational purposes only.
It is NOT a substitute for professional medical advice.
Always consult a certified doctor for real medical concerns.


🚀 Future Enhancements

🏥 Doctor recommendation system

🌍 Multi-language support

📊 Health report analysis

📱 Mobile application
>>>>>>> 1bdbde1cf229f8c173075a2042798ee03d7487e6
