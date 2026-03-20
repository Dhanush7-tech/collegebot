# 🎓 CollegeBot

CollegeBot is an intelligent chatbot that helps students explore courses and colleges based on their academic profile.

---

## 🚀 Features
- 🤖 Interactive chatbot (CLI + API)
- 🎓 Multi-stream support (Engineering, Medical, Pharmacy, etc.)
- 📚 Course recommendation system
- 🏫 College search engine
- 📊 Detailed college information

---

## 🛠️ Tech Stack
- Python
- FastAPI
- JSON
- React (Frontend - in progress)

---

## ▶️ How to Run

### 🔹 CLI Version
bash
python backend/Main.py

(DOWNLOAD ALL THE FILES IN YOUR PC AND FOLLOW THE BELOW STEPS TO TEST THE API)
->API Backend(Terminal)
cd backend
python -m uvicorn api:app --reload

Open browser:(Open the below link)
http://127.0.0.1:8000/docs


---

## 🌐 API Endpoints
- `/chat` → chatbot interaction
- `/courses/{stream}` → courses list
- `/colleges/{course}` → colleges list
- `/college/{college_name}` → details

---

## 📂 Project Structure

collegebot/
│── backend/
│── data/
│── README.md

---

## 📌 Future Improvements
- 🌐 React Frontend UI
- 🧠 AI-based recommendations
- 📱 Mobile responsive design

---

## 👨‍💻 Author
V DHANUSH
