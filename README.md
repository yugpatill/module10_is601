
# Module 10 — Secure User Model, Pydantic Validation, Database Testing & Docker Deployment

This project enhances a FastAPI application by implementing a secure user system using SQLAlchemy models, Pydantic validation, password hashing, and JWT authentication. It also includes unit tests, integration tests with PostgreSQL, and a full CI/CD pipeline that builds, scans, and deploys the Docker image to Docker Hub.

## 🚀 Running Tests Locally

### 1️⃣ Create and activate a virtual environment
```bash
python3 -m venv venv
source venv/bin/activate

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Start PostgreSQL using Docker

docker compose up -d

4️⃣ Run all tests

pytest


Docker Hub Repository:
https://hub.docker.com/r/yugpatil/module10_is601


📝 Reflection

This assignment helped me understand how to design secure backend systems with FastAPI and SQLAlchemy. I learned how to use password hashing, validate user input with Pydantic, and build both unit and integration tests using a real PostgreSQL database. The most challenging part was configuring Docker with PostgreSQL and ensuring the GitHub Actions workflow ran consistently.

📸 Screenshots

Screenshots for GitHub Actions, Docker Hub deployment, and test results are stored here:

https://github.com/yugpatill/module10_is601/tree/main/screenshots

---
