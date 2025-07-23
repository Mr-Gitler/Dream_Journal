# Dream Journal

A web-based Dream Journal app built with Flask and SQLAlchemy.
Record, edit, and manage your dreams with an intuitive interface, 
including a recycle bin for deleted dreams and support for categories, moods, tags, and lucid dreams.

## Features

- Add, edit, and delete dream entries
- Restore deleted dreams from the recycle bin
- Organize dreams by category, mood, and tags
- Mark dreams as lucid
- Responsive, modern UI with dark mode support
- SQLite database for easy setup

## Screenshots
*(Add your own screenshots here!)*

## Getting Started

### Prerequisites
- Python 3.8+
- pip

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Mr-Gitler/Dream_Journal.git
   cd Dream_Journal
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   python app.py
   ```
4. Open your browser and go to [http://localhost:5000] (http://localhost:5000)

## Project Structure
```
app.py              # Main Flask app
requirements.txt    # Python dependencies
README.md           # Project documentation
/templates/         # HTML templates
/static/            # Static files (CSS, JS, images)
```

## Deployment
You can deploy this app to platforms like Render, Railway, or Heroku.

### Example Procfile (for Heroku/Render)
```
web: python app.py
```

## License
MIT (add your own license if needed)

---
*Made with Flask & SQLAlchemy* 
