

<<<<<<< HEAD

# 🤖 ChittiGPT – Personalized AI Chatbot using Gemini

A minimalist, privacy-focused chatbot featuring user authentication and persistent chat history, powered by Google's Gemini AI. Built with Flask and pure HTML/CSS, ChittiGPT delivers a clean, secure, and personal AI experience — all without JavaScript.

# 🤖 ChittiGPT – Personalized AI Chatbot using Gemini

A minimalist, privacy-focused chatbot featuring user authentication and persistent chat history, powered by Google's Gemini AI. Built with Flask and pure HTML/CSS, ChittiGPT delivers a clean, secure, and personal AI experience.


## ✨ Key Features

### 🔐 Secure Authentication
- User registration and login
- Passwords hashed using Werkzeug
- Session-based login flow

### 💬 Smart Chat Handling
- Each user has separate chat history
- Unique chat IDs and titles
- Titles generated automatically by AI

### 🧠 Gemini AI Integration
- Uses Gemini 1.5 Flash for natural, fast responses
- Prompt-to-title summarization
- Error handling for API failures

<<<<<<< HEAD
### 🎨 Dark Minimal UI (No JavaScript)

### 🎨 Dark Minimal UI 
- Pure HTML/CSS interface
- Responsive layout
- Top-right logout and center greeting

## 🛠 Installation Guide

### 🔧 Prerequisites
- Python 3.8+
- Google Gemini API Key
- pip (Python package manager)

### ⚙️ Setup Instructions

1. Clone the repository
   ```bash
   git clone https://github.com/bhuvi6/chittigpt.git
   cd chittigpt
   ```

2. Create a virtual environment
   ```bash
   python -m venv venv
   ```

3. Activate the environment
   - **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - **macOS/Linux**:
     ```bash
     source venv/bin/activate
     ```

4. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

5. Configure your environment  
   Create a `.env` file in the root folder and add:
   ```
   GEMINI_API_KEY=your_gemini_api_key_here
   SECRET_KEY=your_flask_secret_key_here
   ```

## 🚀 Usage Guide

1. Start the Flask server
   ```bash
   python app.py
   ```

2. Open in your browser
   ```
   http://localhost:5000
   ```

3. Chatbot Flow
   - Sign up or log in
   - Start new chats or continue old ones
   - View/delete your chat history
   - Logout securely

## 📂 Project Structure

```
chittigpt/
├── app.py            # Flask app logic
├── .env              # API keys & secret key
├── users.json        # Stores registered users
├── requirements.txt  # Python dependencies
└── templates/        # Frontend HTML templates
    ├── index.html    # Main chatbot page
    ├── login.html    # Login form
    └── signup.html   # Signup form
```

## 🔧 Configuration Notes

### Gemini API Setup
- Get your key from Google AI Studio
- Paste it into `.env` like this:
  ```
  GEMINI_API_KEY=your_key
  ```

### Security
- Keep `.env` out of version control
- Use strong `SECRET_KEY`
- Use hashed passwords (already implemented)

---

🧑‍💻 **Author**: Bhuvaneswari V  
📅 **Created for**: K-Hub 2025–26 Recruitment
```

