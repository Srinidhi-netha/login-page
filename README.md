Flask Login & Registration System
This is a simple Flask web application that allows users to register and log in using an SQLite database. It features clean HTML/CSS design, flash messages for user feedback, and a modular Python backend.

📁 Project Structure
graphql
Copy
Edit
login/
├── app.py              # Main Flask app
├── init_db.py          # Initializes the SQLite database
├── users.db            # Auto-created SQLite DB
└── templates/
    ├── login.html      # Styled login page
    └── register.html   # Styled registration page
🚀 Getting Started
1. Install Flask
nginx
Copy
Edit
pip install flask
2. Initialize the database
nginx
Copy
Edit
python init_db.py
You’ll see:

nginx
Copy
Edit
Database initialized.
3. Run the app
nginx
Copy
Edit
python app.py
Open your browser and go to:

arduino
Copy
Edit
http://127.0.0.1:5000/register
✅ Features
User Registration & Login with SQLite

Flash messages for success/error

Light yellow background with modern form styling

Easy to customize and extend

🔧 To Improve
Add password hashing (recommended!)

Add user sessions and logout functionality

Switch to Bootstrap for a responsive layout

