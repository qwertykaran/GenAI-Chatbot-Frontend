# 💬 GenAI Healthcare Frontend

*Engage with the GenAI Healthcare Chatbot through a clean, modern React interface.*

---

## 🎯 Project Overview

This React application provides a user-friendly chat interface for the **GenAI Healthcare Chatbot** backend.  
Users can ask healthcare-related questions and receive intelligent, context-aware responses powered by a FastAPI backend integrated with Neo4j and Hugging Face models.
This project was certified by **Intel**.

[View Certificate (PDF)](INTEL_CERTIFICATE.pdf)


---

## ✨ Features

- Responsive and modern chat UI with message bubbles  
- Smooth scrolling to latest messages  
- Typing indicator and error handling  
- Connects to backend API to send user questions and receive answers  
- Keyboard support: send message by pressing Enter  
- Stylish, accessible design with clear role distinction (User vs Bot)

---

## 🛠 Getting Started

### Prerequisites

- Node.js 14+  
- npm or yarn package manager

### Installation

```bash
git clone https://github.com/qwertyfrontend/genai-chatbot-frontend.git
cd genai-healthcare-frontend
npm install
```


---

### Environment Variables

Create a `.env` file in the root directory with the following content:

```bash
REACT_APP_BACKEND_URL=http://localhost:8000
```

This URL points to your locally running backend API.

---

### Running the Frontend

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to interact with the chatbot.

---

## 💡 Usage

- Type your healthcare-related questions into the input box at the bottom.  
- Press **Enter** or click **Send** to submit your question.  
- Chat messages appear in bubbles aligned left (Bot) or right (User).  
- The chat window automatically scrolls to show the latest messages.  
- If the backend is unreachable, an error message will be displayed.

---

## 📸 Screenshots

![Chat Interface](./screenshots/chat-ui.png)  
*Clean and modern chat UI with distinct user and bot messages.*

---

## 🚧 Known Issues

- Deployment pending (frontend currently runs locally)  
- UI enhancements and accessibility improvements planned

---

## 🔮 Future Enhancements

- Add user authentication and session management  
- Integrate voice input/output for hands-free interaction  
- Deploy frontend on platforms like Netlify or Vercel  
- Add analytics to track user interactions and improve chatbot responses

---

## 📎 Links

- Backend Repo: [genai-healthcare-backend](https://github.com/qwertykaran/genai-chatbot-backend)

---

## 📄 License

MIT License © 2025 Karan Soni
