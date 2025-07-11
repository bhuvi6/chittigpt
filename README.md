Absolutely, Bhuvi! Here's your **final `README.md`** for the **ChittiGPT** project — clean, professional, and submission-ready:

---

```markdown
# 🤖 ChittiGPT – Your Personal AI Chatbot

ChittiGPT is a full-stack conversational AI chatbot built with **Flask**, powered by **Gemini AI**, and styled with a responsive dark-themed UI. It supports multiple user accounts, chat history, smart chat titles, and conversation management features like renaming and deleting chats.

---

## 🚀 Features

- 🔐 User Signup/Login with session-based authentication
- 💬 Gemini-powered chat responses using `gemini-1.5-flash`
- 📂 Multiple chat histories per user (stored as JSON files)
- 🧠 Smart auto-titling for new conversations
- ✏️ Rename chats with inline modal
- 🗑️ Delete conversations from the sidebar
- 📱 Mobile-responsive layout with hamburger menu
- 🌙 Dark-themed modern UI
- 🔓 Logout functionality

---

## 🛠️ Technologies Used

| Layer          | Stack                       |
|----------------|-----------------------------|
| Backend        | Python, Flask               |
| AI Model       | Gemini 1.5 Flash (Google)   |
| Frontend       | HTML, CSS (No JS frameworks)|
| Database       | JSON-based local storage    |
| Security       | Password hashing with Werkzeug |
| Deployment     | Flask Dev Server (localhost) |
| Version Control| Git & GitHub                |

---

## 🧾 Folder Structure

```

chittigpt/
│
├── templates/
│   ├── index.html         # Main chat UI
│   ├── login.html         # Login page
│   └── signup.html        # Signup page
│
├── app.py                 # Flask application
├── users.json             # Registered user info
├── chat\_history\_\*.json    # Chat histories per user
├── .env                   # API key & secret key
└── README.md              # Project overview

````

---

## 📝 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/bhuvi6/chittigpt.git
   cd chittigpt
````

2. **Create a virtual environment**

   ```bash
   python -m venv venv
   venv\Scripts\activate   # On Windows
   ```

3. **Install dependencies**

   ```bash
   pip install flask python-dotenv google-generativeai
   ```

4. **Set up your `.env` file**

   ```env
   GEMINI_API_KEY=your_gemini_api_key
   SECRET_KEY=your_flask_secret_key
   ```

5. **Run the app**

   ```bash
   python app.py
   ```

6. Visit `http://127.0.0.1:5000` in your browser 🎉

---

## 📸 Demo Screenshots

> Add your screenshots here:

* Signup/Login Page
* Chat Interface
* Rename/Delete Chat Menu
* Mobile View

---

##  Made  by Bhuvaneswari

This project was built as part of **K-Hub 2025–26 recruitment** to demonstrate real-world skills in AI, web development, and UI/UX.

---

````

### ✅ Next Steps
- Add this file as `README.md` in your GitHub repo root.
- Push it:
  ```bash
  git add README.md
  git commit -m "Added final README"
  git push origin main
````

Let me know if you'd also like a **short demo video script** or **submission writeup** for the K-Hub team!
