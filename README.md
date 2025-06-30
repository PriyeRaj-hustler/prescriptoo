# 💊 Prescripto – Full Stack Appointment Booking System

**Prescripto** is a full-featured appointment booking platform built for hospitals, clinics, and independent doctors. It provides a three-level authentication system to manage users (patients), doctors, and administrators.

---

## 🚀 Features

### 👤 Patients
- Register and login securely
- Browse available doctors by specialty
- Book, view, and manage appointments
- Receive confirmation and updates

### 🩺 Doctors
- Login to their dedicated dashboard
- View daily appointment schedule
- Track earnings and booking history
- Update personal profile and availability

### 🛠️ Admin
- Manage all appointments in the system
- Add, update, or remove doctor profiles
- View user-doctor interactions and statistics

---

## 🏗️ Tech Stack

### 🌐 Frontend
- React.js
- React Router DOM
- Axios
- Material UI / Tailwind CSS

### 🖥️ Backend
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT for Authentication
- Bcrypt for password hashing

---

## 📁 Project Structure

prescripto/
├── admin/ # Admin dashboard interface
├── backend/ # Node.js backend with REST APIs
└── clientend/ # Patient and doctor frontend UI

yaml
Copy
Edit

---

## 🔐 Authentication Levels

1. **Patient Login** – Book/manage appointments  
2. **Doctor Login** – View appointments, update profile, track earnings  
3. **Admin Login** – Manage all system data, doctors, and appointments  

---

## 🛠️ Installation & Setup

### Prerequisites
- Node.js & npm
- MongoDB (local or Atlas)
- Git & terminal
- Code editor (e.g. VS Code)

### Steps

```bash
# Clone the repository
git clone https://github.com/your-username/prescripto.git
cd prescripto

# Setup backend
cd backend
npm install

# Setup frontend (clientend)
cd ../clientend
npm install

# Setup admin dashboard
cd ../admin
npm install
```
Environment Variables
Create a .env file in the /backend folder:

```bash
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
```
Run the App
```
bash
# Run backend server
cd backend
npm start

# Run patient & doctor frontend
cd ../clientend
npm start

# Run admin dashboard
cd ../admin
npm start
```
## 📸 Screenshots
Add your app screenshots here:

Patient booking UI

Doctor dashboard

Admin panel

## 📌 Future Enhancements
Email & SMS notifications

Integrated payment gateway

Video consultation module

Patient health history management

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue to discuss what you would like to change.

## 📄 License
This project is licensed under the MIT License.

## 👨‍💻 Author
Priye Raj
3rd Year, Electrical Engineering
NIT Silchar
📧 priyer_ug_22@ee.nits.ac.in
📞 7677640870
