🚀 Task Manager App
A simple Full-Stack Task Manager Application built with:

Backend: FastAPI + SQLite

Frontend: React.js + TailwindCSS

Features: Add, Edit, Delete, Mark as Completed, Toast notifications, Database support (SQLite/PostgreSQL Ready)

📂 Project Structure
task-manager-app/
│
├── backend/
│   ├── main.py             # FastAPI app
│   ├── models.py           # SQLAlchemy models
│   ├── database.py         # DB connection (SQLite/PostgreSQL)
│   ├── schemas.py          # Pydantic schemas
│   └── requirements.txt    # Backend dependencies
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── App.js          # Main React App
│   │   ├── index.js
│   │   └── components/     # (Optional) components like TaskList, TaskForm
│   ├── package.json
│   └── tailwind.config.js
│
└── README.md
💡 Features
✔️ Add New Task
✔️ Edit Existing Task
✔️ Delete Task
✔️ Mark Task as Completed
✔️ SQLite/PostgreSQL Supported
✔️ Toast Notifications
✔️ Clean UI with TailwindCSS

🔧 Tech Stack
Frontend	Backend	Database
React.js	FastAPI	SQLite (default) / PostgreSQL Ready
TailwindCSS	SQLAlchemy	Alembic for migrations

⚙️ Local Setup
1. Clone this repo:
git clone https://github.com/22MH1A4242/task_manager_app.git
cd task_manager_app
2. Backend Setup (FastAPI + SQLite):
cd backend
python -m venv venv
venv\Scripts\activate  # for Windows
pip install -r requirements.txt
uvicorn main:app --reload
3.Frontend Setup (React + Tailwind):
cd frontend
npm install
npm start
Frontend: http://localhost:3000
Backend: http://127.0.0.1:8000

📦 Build for Production
cd frontend
npm run build

📝 To-Do (Optional)
 PostgreSQL DB Switch via DATABASE_URL

 User Authentication

 Deploy on Render/Netlify/Vercel

🙏 Acknowledgements
FastAPI Docs

React Docs

TailwindCSS Docs

