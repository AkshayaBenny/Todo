
# ✅ TODO API with FastAPI

This project is a simple TODO API built using **Python FastAPI**, **Tortoise ORM**, and an **SQLite** database (`todo.db`).

---

## 📁 Project Structure

```
project/
│
├── myenv/                 # Python virtual environment
├── todo.db                # SQLite database
├── requirements.txt       # List of dependencies
├── main.py                # Entry point of the application
│
├── app/
│   └── main.py            # Sets up DB and default root API
│
└── api/
    ├── routes/            # All API route definitions
    ├── models/            # Database models
    └── schemas/           # Pydantic schemas
```

---

## ⚙️ Setup Instructions

### 1. Create a Virtual Environment

```bash
python3 -m venv myenv
source myenv/bin/activate
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the Project

```bash
python main.py
```

This will start the FastAPI server using `uvicorn`.

---

## 🛠 Tech Stack

- **FastAPI** – for building the web API
- **Tortoise ORM** – for database interactions
- **Pydantic** – for data validation and serialization
- **Uvicorn** – ASGI server
- **SQLite** – lightweight embedded database (`todo.db`)

---

## 📌 Notes

- **API Endpoints** are defined in `api/routes/`.
- **Models** (Tortoise ORM) are in `api/models/`.
- **Schemas** (Pydantic) are in `api/schemas/`.
- `app/main.py` sets up the database connection and default root endpoint.
- `main.py` is used to run the entire project.

---

## ▶️ How to Activate the Environment

```bash
source myenv/bin/activate
```

Then run the app using:

```bash
python main.py
```

---
