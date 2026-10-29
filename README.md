# HRMS (MERN)

## Backend
cd server
cp .env.example .env     (set JWT_SECRET, MONGO_URI)
npm install
npm run dev              (runs on http://localhost:5000)

## Frontend
cd client
npm install
npm run dev              (runs on http://localhost:5173, /api is proxied to the backend)

## Roles
- First registered user becomes HR.
- HR opens "Manage Users" to make others manager/hr and assign each employee a manager.
- Managers only see leave requests and attendance of employees assigned to them.
