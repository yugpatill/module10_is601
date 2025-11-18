**Module 10 — Secure User Model, Pydantic Validation, Database Testing & Docker Deployment**

This project extends a FastAPI application by implementing a secure user system, including a SQLAlchemy model, Pydantic validation, password hashing, and JWT authentication.
It also includes database-backed integration tests, a full CI/CD pipeline, and automatic Docker image deployment.


**Running Tests Locally**

1️⃣ Create and activate a virtual environment

python3 -m venv venv
source venv/bin/activate

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Start Postgres

docker compose up -d

4️⃣ Run all tests

pytest


**Reflection**

This assignment helped me understand how to design secure backend systems using FastAPI and SQLAlchemy.
I learned to implement password hashing, validation with Pydantic, and structure unit and integration tests that interact with a real database.
The most challenging part was configuring Docker with Postgres and ensuring tests ran consistently both locally and in GitHub Actions.
