#  Fullstack AI Chatbot (Rasa + React + TailwindCSS)

A fullstack AI chatbot with a modern web interface, built using Rasa for natural language processing and React for the frontend.
The project includes authentication, conversational interaction, and a clean user experience.

---

##  Features

*  AI-powered chatbot using Rasa
*  Real-time conversational interface
*  User authentication (login & register)
*  Modern UI built with React and TailwindCSS
*  Fast development setup with Vite

---

##  Tech Stack

### Frontend

* React
* TailwindCSS
* Vite

### Backend

* Python
* Rasa

---

##  Project Structure

```
ai-chatbot/
│
├── backend/        # Rasa chatbot (NLP, actions, training data)
├── frontend/       # React web application
├── system/         # Optional scripts (e.g. .bat launcher)
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ai-chatbot.git
cd ai-chatbot
```

---

### 2. Backend (Rasa)

```bash
cd backend
pip install -r ../requirements.txt
rasa train
rasa run
```

In another terminal:

```bash
rasa run actions
```

---

### 3. Frontend (React)

```bash
cd frontend
npm install
npm run dev
```

---

## ▶️ Usage

1. Start the backend (Rasa server + actions)
2. Run the frontend
3. Open the app in your browser
4. Start chatting with the AI 🤖

---

## 📸 Screenshots

*Add screenshots of your chatbot UI here*

---

##  Notes

* Make sure Python and Node.js are installed
* Do not upload sensitive files like `.env` or `node_modules`
* Models are not included — run `rasa train` to generate them

---

## License

This project is open-source and available under the MIT License.

---

## Author

Developed by Edgar Adrian
