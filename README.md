 # 🏠 AddisNest – House Rental Marketplace

AddisNest is a modern **house rental marketplace system** for Addis Ababa.  
It connects **renters, owners, brokers, and admins** in a secure, user-friendly platform.  
The project is built with a **full-stack JavaScript** stack:

- **Frontend:** Vite + React + Tailwind CSS  
- **Backend:** Node.js + Express.js  
- **Database:** PostgreSQL  
- **Authentication:** JWT + bcrypt  
- **Deployment:** Vercel (planned)

---

## 🚀 Features

### 👤 Users (Renters)
- Register, login, and manage profile  
- Search, filter, and browse property listings  
- View property details (photos, location, owner/broker info)  
- Save properties to favorites  
- Book or send inquiries to owners/brokers  
- Manage bookings (view, cancel)  
- Write reviews and give ratings  

### 🏡 Owners
- Add, edit, and delete property listings  
- Upload/manage property images  
- View and respond to bookings  
- Dashboard for managing listings & bookings  

### 🤝 Brokers
- Manage multiple property listings (on behalf of owners)  
- Coordinate with tenants and owners  
- Dashboard for client and listing management  

### 🛡️ Admin
- Admin dashboard (users, properties, bookings, stats)  
- Manage users: block/unblock, role changes, delete  
- Manage properties: approve/reject, edit, delete  
- Manage bookings: view/cancel suspicious bookings  
- Review & report moderation (delete inappropriate reviews)  
- System settings & audit logs for admin actions  

---

## 🏗️ Tech Stack

**Frontend**
- [Vite](https://vitejs.dev/)  
- [React](https://react.dev/)  
- [Tailwind CSS](https://tailwindcss.com/)
- [React Router](https://reactrouter.com/) 

**Backend**
- [Node.js](https://nodejs.org/) 
- [Express.js](https://expressjs.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [pg](https://www.npmjs.com/package/pg)  
- [bcrypt](https://www.npmjs.com/package/bcrypt) 
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) 
- [helmet](https://helmetjs.github.io/) 
- [express-validator](https://express-validator.github.io/) 

---

## 📂 Project Structure

AddisNest/
├── frontend/                   # Frontend (Vite + React + Tailwind)
│   ├── public/                 # Static assets
│   ├── src/                    
│   │   ├── assets/             # Images, icons, fonts
│   │   ├── components/         # Reusable UI components
│   │   ├── pages/              # Page-level components (Home, Listings, Profile, Admin Dashboard, etc.)
│   │   ├── layouts/            # Shared layouts (Navbar, Footer, Sidebar)
│   │   ├── context/            # React Context API (Auth, Theme, etc.)
│   │   ├── hooks/              # Custom hooks (useAuth, useFetch, etc.)
│   │   ├── utils/              # Utility functions/helpers
│   │   ├── services/           # API calls to backend
│   │   ├── App.jsx             # Main React component
│   │   ├── main.jsx            # Entry point for Vite
│   │   └── index.css           # Tailwind & global styles
│   ├── package.json
│   └── vite.config.js
│
├── backend/                    # Backend (Node.js + Express + PostgreSQL)
│   ├── src/
│   │   ├── config/             # DB connection, environment configs
│   │   ├── models/             # Sequelize/Prisma models for Postgres
│   │   ├── routes/             # Express routes (auth, users, listings, bookings, admin, etc.)
│   │   ├── controllers/        # Route controllers (business logic)
│   │   ├── middlewares/        # Auth, validation, error handling
│   │   ├── services/           # External services (email, payment, cloud storage)
│   │   ├── utils/              # Helpers (JWT, password hashing, etc.)
│   │   ├── app.js              # Express app setup
│   │   └── server.js           # Entry point (start server)
│   ├── package.json
│   └── .env.example            # Example environment variables
│
├── docs/                       # Documentation (design, API docs, DB schema)
│   ├── api-reference.md
│   ├── db-schema.png
│   └── system-architecture.md
│
├── scripts/                    # Deployment & automation scripts
│
├── .gitignore
├── README.md                   # Project overview
├── LICENSE
└── package.json                # Root dependencies if using workspaces


---

## ⚙️ Installation & Setup

### Prerequisites
- [Node.js](https://nodejs.org/) >= 18
- [PostgreSQL](https://www.postgresql.org/) >= 14
- [Git](https://git-scm.com/)

### 1. Clone the repository
```bash
git clone https://github.com/Ashenafi-Bancha/AddisNest.git
cd AddisNest
```
### 2. Backend Setup
cd backend
cp .env.example .env   # configure DB connection, JWT secrets, etc.
npm install
npm run dev

### 3. Frontend Setup
cd frontend
npm install
npm run dev

### 4. Database Migrations



## 👨‍💻 Author
Ashenafi Bancha Bassa | Computer Science Student at Addis Ababa University
