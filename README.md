# Employee Attendance & Analytics API

A FastAPI and MongoDB-backed application built as part of the HROne Software Engineer Trainee technical assignment. It manages employee records, daily attendance punch-ins/outs, administrative corrections with full audit trails, and advanced analytics via MongoDB aggregation pipelines.

---

## Prerequisites
- Python 3.11+
- Git
- MongoDB 6.0+ (Local Docker container or MongoDB Atlas free tier)

---

## Local Setup & Running

1. **Clone or Extract the Repository:**
   Open your project root directory containing `app/main.py` and `requirements.txt`.

2. **Create and Activate Virtual Environment:**
   ```bash
   python -m venv .venv
   # On Windows (PowerShell):
   .\.venv\Scripts\Activate
   # On macOS/Linux:
   source .venv/bin/activate
