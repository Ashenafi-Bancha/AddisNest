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
│
├── backend/ # Express.js + PostgreSQL API
│ ├── src/
│ │ ├── controllers/ # Route handlers
│ │ ├── middleware/ # Auth & role-based guards
│ │ ├── models/ # DB queries
│ │ ├── routes/ # API routes
│ │ ├── utils/ # Helpers
│ │ └── server.js # App entry
│ ├── .env.example # Backend environment variables
│ └── package.json
│
├── frontend/ # Vite + React + Tailwind
│ ├── src/
│ │ ├── components/ # Reusable UI
│ │ ├── pages/ # Pages (Home, Dashboard, Admin, etc.)
│ │ ├── services/ # API calls
│ │ └── main.jsx
│ ├── tailwind.config.js
│ └── package.json
│
├── README.md



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
