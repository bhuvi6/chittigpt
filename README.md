
# 🤖 ChittiGPT – Your Personal AI Chatbot



“ChittiGPT is a Flask-based chatbot platform styled with custom HTML/CSS, backed by MongoDB for storing user chat history, and powered by Google’s Gemini API for generating AI responses — all wrapped in a mobile-responsive UI with dynamic sidebar navigation.”

## 🌟 Key Features

### 🔒 User Management
- Secure signup/login with session-based authentication
- Password hashing with Werkzeug
- Protected routes for authenticated users only

### 💬 Smart Chat Experience
- Powered by Gemini 1.5 Flash for natural conversations
- Automatic chat title generation from first message
- Edit chat titles with inline modal
- Delete conversations from sidebar

### 📚 Data Management
- Multiple chat histories per user
- JSON-based local storage
- Persistent conversation history

### 🎨 Modern UI
- Clean dark-themed interface
- Fully responsive design
- Hamburger menu for mobile
- No JavaScript frameworks (pure HTML/CSS)

## 🛠 Technology Stack

| Component        | Technology               |
|------------------|--------------------------|
| **Backend**      | Python 3.8+, Flask       |
| **AI Engine**    | Gemini 1.5 Flash         |
| **Frontend**     | HTML5, CSS3 (No JS)      |
| **Database**     | JSON files               |
| **Authentication**| Flask-Login, Werkzeug   |
| **Deployment**   | Flask Development Server |

## 📂 Project Structure

```
chittigpt/
├── templates/            # Frontend templates
│   ├── index.html        # Main chat interface
│   ├── login.html        # Login page
│   └── signup.html       # Registration page
├── static/               # Static assets (CSS, images)
│   └── styles.css        # Main stylesheet
├── app.py                # Flask application
├── users.json            # User credentials database
├── chat_histories/       # User conversation storage
│   └── user_*.json       # Individual chat histories
├── .env                  # Environment configuration
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Google Gemini API key
- pip package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bhuvi6/chittigpt.git
   cd chittigpt
   ```

2. **Set up virtual environment**
   ```bash
   python -m venv venv
   # Windows:
   venv\Scripts\activate
   # macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure environment**
   Create `.env` file with:
   ```env
   GEMINI_API_KEY=your_actual_api_key
   SECRET_KEY=your_secure_secret_key
   ```

5. **Launch the application**
   ```bash
   python app.py
   ```
   Open your browser to: `http://localhost:5000`

## 📝 Usage Guide

1. **Account Creation**
   - Register a new account via signup page
   - Log in with your credentials

2. **Chat Interface**
   - Start new conversations with the "+" button
   - Messages are automatically saved
   - Edit chat titles by clicking the pencil icon
   - Delete chats from the sidebar

3. **Session Management**
   - Secure logout from top-right menu
   - Return to continue previous conversations

## 🔧 Configuration Options

Customize your experience by modifying:
- `app.py`: Change port, debug mode, or routes
- `styles.css`: Adjust colors, layout, or responsive breakpoints
- `.env`: Set different API keys for development/production


## 👩‍💻 Author & Credits

**Bhuvaneswari V**  
Developed for **K-Hub 2025–26 Recruitment**  
[GitHub Profile](https://github.com/bhuvi6) | [LinkedIn](https://www.linkedin.com/in/bhuvaneswari-vasamsetti/)  

---

⭐ **Star this repo** if you find it useful!  
🐞 **Report issues** in the GitHub tracker  
💡 **Suggest improvements** via pull requests
```

