# 🤖 GROOT Chatbot

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Flask](https://img.shields.io/badge/Flask-Framework-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-green)
![Excel](https://img.shields.io/badge/Excel-QA%20Database-yellow)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A simple and interactive **Flask-based chatbot** that answers questions from a pre-defined **Excel Q&A database**.  
The chatbot comes with a **modern, responsive HTML/CSS UI** and remembers your name during the conversation using session management.  

---

## 📌 Features
- 🗂 **Excel-based Q&A Database** — Easy to update without touching the code.
- 💬 **Conversational Memory** — Remembers your name across the session.
- 🎨 **Responsive & Stylish UI** — Built with HTML, CSS, and animations.
- ⚡ **Real-time Responses** — AJAX-powered for smooth interaction.
- 🔄 **Session Reset** — Type `"exit"` to restart the conversation.

---

## 🛠 Tech Stack
- **Backend:** Python, Flask  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** Excel (.xlsx) via Pandas & OpenPyXL  

---

## 📂 Project Structure
```
├── app.py                # Flask backend application
├── index.html            # Frontend UI template
├── qa_database.xlsx      # Q&A data source
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### 2️⃣ Create Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate   # For Mac/Linux
venv\Scripts\activate      # For Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application
```bash
python app.py
```

The app will start on **http://127.0.0.1:5000/**

---

## 📝 Usage
1. Open the chatbot in your browser.  
2. Type your query or introduce yourself (e.g., _"My name is John"_).  
3. The bot will:
   - Respond based on **qa_database.xlsx**.
   - Remember your name until you exit.
4. Type **`exit`** to restart.

---

## 📊 Q&A Database Format
Your **qa_database.xlsx** must have:
| Question | Answer |
|----------|--------|
| Hello    | Hi there! How can I help you today? |
| What is your name? | I am Groot! |

---

## 📜 License
This project is licensed under the **MIT License** — feel free to use and modify.
