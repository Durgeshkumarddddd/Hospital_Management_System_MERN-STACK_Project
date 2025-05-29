# 🏨 Hotel Management System (MERN Stack)

A full-featured **Hotel Management System** built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). This project includes:

- ✅ Customer Frontend Interface
- ✅ Admin Dashboard for Hotel Staff
- ✅ Secure Backend API
- ✅ MongoDB for persistent data storage

---

## 📌 Key Features

### 👨‍💼 Admin Dashboard
- Login/Logout for Admin
- Manage Room Types & Availability
- View All Bookings
- View All Customers
- Add/Edit/Delete Rooms

### 🧑 Customer Frontend
- Register/Login
- Search Available Rooms by Date, Type
- Book Rooms
- View Booking History
- Responsive Design

### 🔧 Backend API
- RESTful APIs using Express.js
- JWT-based Authentication
- MongoDB for NoSQL storage
- Mongoose for data modeling
- Secure Passwords using bcrypt

---

## 📁 Folder Structure
hotel-management-system/
│
├── client/ # React.js frontend for customers
│ └── src/
│ ├── components/
│ ├── pages/
│ ├── App.js
│ └── ...
│
├── admin-dashboard/ # React.js frontend for admin panel
│ └── src/
│ ├── components/
│ ├── pages/
│ ├── App.js
│ └── ...
│
├── server/ # Express.js backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ └── index.js
│
└── README.md

yaml
Copy
Edit

---

## ⚙️ Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/hotel-management-system.git
cd hotel-management-system
🚀 Running the Application
📦 Backend Setup
bash
Copy
Edit
cd server
npm install
touch .env
Inside .env, add:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongo_uri
JWT_SECRET=your_secret_key
Start server:

bash
Copy
Edit
npm run dev
🌐 Frontend (Customer) Setup
bash
Copy
Edit
cd client
npm install
npm start
🧑‍💼 Admin Dashboard Setup
bash
Copy
Edit
cd admin-dashboard
npm install
npm start
🧪 Sample API Routes
Method	Endpoint	Description
POST	/api/auth/register	Register Customer
POST	/api/auth/login	Login Customer
GET	/api/rooms/available	Check Room Availability
POST	/api/bookings	Create New Booking
GET	/api/admin/bookings	Get All Bookings (Admin)
DELETE	/api/admin/room/:id	Delete Room (Admin)

🔐 Authentication
JWT Tokens for secure login

bcrypt for password hashing

Role-based Access Control (Customer/Admin)

📸 Screenshots (Add your actual screenshots)
Customer Homepage

Booking Page

Admin Dashboard

Room Management Panel

🎯 Future Scope
🌐 Deploy frontend (Vercel/Netlify), backend (Render/Railway)

💳 Payment Gateway (Razorpay/Stripe)

📧 Email Notifications

📈 Admin Analytics (Charts, Reports)

👨‍💻 Developer
GitHub: your-username

LinkedIn: your-linkedin-profile

Portfolio: your-portfolio-link

📜 License
Licensed under MIT License

“An efficient, scalable, and user-friendly hotel booking solution using the MERN stack.”

yaml
Copy
Edit

---

Would you like help setting up:
- Live deployment scripts for Render/Vercel?
- `env` sample files for frontend/backend?
- API documentation using Swagger/Postman?

Let me know, sir, I can help you complete every part of the system.








