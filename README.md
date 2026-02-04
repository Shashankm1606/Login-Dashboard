A lightweight, full-stack authentication system built with a Flask back end and a dynamic Vanilla JavaScript front end. This project demonstrates secure user routing, session management, and responsive UI design.

🏗️ Tech Stack
Front End: HTML5, CSS3, JavaScript (ES6+)

Back End: Flask (Python)

Database: SQLite (default with Flask) or SQLAlchemy

Styling: Custom CSS (Responsive Design)

🌟 Key Features
Asynchronous Login: Uses the JavaScript fetch() API to communicate with Flask without refreshing the page.

Session Management: Secure user sessions powered by Flask-Session.

Protected Routes: Dashboard access is restricted to authenticated users only.

Password Security: (Optional/Recommended) Implements password hashing using Werkzeug or bcrypt.

Real-time Validation: Front-end form validation for a better user experience.
project workflow 
login-dashboard/
├── static/          # CSS and Client-side JS
│   ├── css/
│   └── js/
├── templates/       # HTML files (index.html, dashboard.html)
├── app.py           # Main Flask application (Routes & Logic)
├── database.db      # SQLite database file
└── README.md
