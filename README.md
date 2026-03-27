# Spendly

A personal expense tracker that helps you understand where your money goes.

## Quick Start

```bash
pip install -r requirements.txt
python app.py
```

Open [http://localhost:5001](http://localhost:5001) in your browser.

## What It Does

- **Landing page** — Introduces the app with a hero section, features, and a video demo modal
- **Register / Login** — Create an account or sign in to your existing one
- **Track expenses** — Add, edit, and delete your daily expenses
- **See spending patterns** — View breakdowns by category and time period

## Project Structure

```
├── app.py              # Main Flask app and routes
├── database/           # Database setup and models
├── templates/          # HTML pages
│   ├── base.html       # Shared layout (nav, footer)
│   ├── landing.html     # Homepage
│   ├── register.html   # Sign up page
│   ├── login.html      # Sign in page
│   ├── terms.html      # Terms and Conditions
│   └── privacy.html    # Privacy Policy
├── static/
│   ├── css/style.css   # All styles
│   └── js/main.js      # JavaScript (modal, etc.)
└── requirements.txt    # Python dependencies
```

## Tech Stack

- **Backend:** Flask (Python)
- **Frontend:** HTML, CSS, Vanilla JavaScript
- **Database:** SQLite
