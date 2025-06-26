Flask Login & Registration System
This is a simple Flask web application that allows users to register and log in using an SQLite database. It features clean HTML/CSS design, flash messages for user feedback, and a modular Python backend.

📁 Folder Structure
bash
Copy
Edit
login/
├── app.py              # Main Flask app
├── init_db.py          # Script to initialize SQLite database
├── users.db            # SQLite database (auto-created)
└── templates/
    ├── login.html      # Login page
    └── register.html   # Registration page
🚀 How to Run
Install dependencies (Flask):

bash
Copy
Edit
pip install flask
Initialize the database:

bash
Copy
Edit
python init_db.py
Start the Flask app:

bash
Copy
Edit
python app.py
Open your browser and visit:

arduino
Copy
Edit
http://127.0.0.1:5000/register
💡 Features
User Registration & Login

SQLite Database Integration

Flash messages for feedback

Responsive UI with modern CSS

Easy to extend (e.g., password hashing, sessions)

