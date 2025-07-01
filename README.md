# ⚙️ Fullstack CI/CD Demo

A simple fullstack project with:

- **Frontend**: Static HTML/CSS website
- **Backend**: Python Flask API with automated tests
- **CI/CD**: GitHub Actions workflows for both frontend and backend folders (runs only on changes)

---

## 🚀 Live Preview (Coming Soon)

> Deploy instructions pending for frontend (Netlify/GitHub Pages) and backend (EC2/Render).

---

## ✅ CI/CD Status

| Workflow | Status |
|----------|--------|
| 🖼 Frontend CI | ![Frontend CI](https://github.com/Namangit008/Fullstack-ci-cd-demo/actions/workflows/frontend-ci.yml/badge.svg) |
| 🔧 Backend CI | ![Backend CI](https://github.com/Namangit008/Fullstack-ci-cd-demo/actions/workflows/backend-ci.yml/badge.svg) |

---

## 🧩 Project Structure

Fullstack-ci-cd-demo/
├── frontend/ # Static frontend
│ ├── index.html
│ └── style.css
├── backend/ # Flask backend
│ ├── app.py
│ ├── requirements.txt
│ └── tests/
│ └── test_app.py
└── .github/
└── workflows/ # GitHub Actions
├── frontend-ci.yml
└── backend-ci.yml

---


---

## 🛠 Tech Stack

| Layer     | Tech Used        |
|-----------|------------------|
| Frontend  | HTML, CSS        |
| Backend   | Python (Flask)   |
| Testing   | Pytest           |
| CI/CD     | GitHub Actions   |

---

## 📦 How to Run Locally

### 🖼 Frontend

```bash
cd frontend
# Open index.html in a browser

### 🖼 Backend
cd backend
pip install -r requirements.txt
python app.py

Run Backend Tests
pytest tests/

---





