# toDo_Flask_APP

# 📝 Flask Todo Application

A simple Todo List application built using **Flask**, **Flask-SQLAlchemy**, and **SQLite**. Users can add, update, and delete tasks through a clean web interface.

---

## Features

- Add new todos
- Update existing todos
- Delete todos
- View all todos
- SQLite database integration
- Bootstrap 5 responsive UI

---

## Tech Stack

- Python
- Flask
- Flask-SQLAlchemy
- SQLite
- HTML
- CSS
- Bootstrap 5

---

## Project Structure

```
TODO/
│
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
│
├── templates/
│   ├── base.html
│   ├── index.html
│   └── update.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── test.js
│
├── instance/
│   └── todo.db
│
└── myenv/
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/flask-todo.git
cd flask-todo
```

### Create Virtual Environment

Windows

```bash
python -m venv myenv
```

Activate

```bash
myenv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
python app.py
```

The application will start at

```
http://127.0.0.1:8000
```

---

## Database

The application uses **SQLite**.

Database file:

```
instance/todo.db
```

If the database doesn't exist, create it by running:

```python
with app.app_context():
    db.create_all()
```

---

## Future Improvements

- User Authentication
- Search Todos
- Due Date
- Priority Levels
- Categories
- Dark Mode
- REST API
- Pagination

---

## Requirements

```
Flask
Flask-SQLAlchemy
```

Generate automatically:

```bash
pip freeze > requirements.txt
```

---

## License

This project is open source under the **MIT License**.