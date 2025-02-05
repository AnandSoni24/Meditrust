# MEDITRUST - Doctor Appointment Booking System 🚀

MEDITRUST is an advanced Doctor Appointment Booking System built using the MERN Stack. It provides a seamless and efficient platform for patients, doctors, and administrators to manage healthcare appointments online.

## 🩺 About the Project

MEDITRUST streamlines the process of finding doctors, booking appointments, managing schedules, and online payments while ensuring a smooth experience for all users.

## 🌟 Key Objectives

- **Patients**: Find doctors, book appointments, and make payments.
- **Doctors**: Manage availability, accept/reject appointments.
- **Admin**: Monitor system, manage doctors & appointments.

---

## 🔥 Features

### 📍 Patient Panel

- ✅ **User Registration & Login**: Secure registration and login for users.
- ✅ **Search Doctors**: Find doctors by specialty, location, and availability.
- ✅ **Book/Cancel Appointments**: Easy appointment management for users.
- ✅ **Secure Online Payments**: Integration with Razorpay and Stripe for payments.
- ✅ **View Appointment History**: Keep track of past appointments and reminders.

### 🩺 Doctor Panel

- ✅ **Dashboard**: Monitor earnings and manage schedules.
- ✅ **Accept/Reject Appointments**: Control over appointment approval.
- ✅ **Edit Doctor Profile & Availability**: Update profile details and availability.

### 🛠 Admin Panel

- ✅ **System Overview**: View total patients, doctors, and appointments.
- ✅ **Manage Doctor Records**: Add, edit, or delete doctor details.
- ✅ **Generate Reports & Analytics**: Access comprehensive reports for system monitoring.

---

## 🔐 Security & Compliance

- ✅ **Role-Based Access Control (RBAC)**: Different access levels for patients, doctors, and admins.
- ✅ **Encrypted Authentication using JWT**: Secure login and session management.
- ✅ **Compliance with HIPAA & GDPR**: Ensuring data privacy and protection.

---

## 🛠 Technologies Used

### Frontend:
- **React.js** - For building the user interface.
- **Redux** - State management for smooth app navigation.
- **Tailwind CSS** - Utility-first CSS framework for styling.

### Backend:
- **Node.js** - JavaScript runtime for the backend.
- **Express.js** - Web framework for handling HTTP requests.
- **MongoDB (Mongoose)** - NoSQL database for data storage.
- **JWT Authentication** - Secure user authentication and token-based session management.

### Payment Gateway:
- **Razorpay** - For handling payments securely.
- **Stripe** - Another option for online payments.

### Other Tools:
- **Axios** - For making HTTP requests.
- **React Toastify** - For notification alerts.
- **Cloudinary** - For uploading and managing profile images.

---

## ⚙ Installation & Setup

### Prerequisites

Ensure you have the following installed on your system:

- **Node.js** (>= 14.x) & npm
- **MongoDB** (Local or Atlas)

### 1. Clone the Repository

git clone https://github.com/AnandSoni24/MediTrust.git
cd MediTrust

### 2. Backend Setup
Navigate to the backend directory:  cd backend

Install dependencies:    npm install

Create a .env file with the following variables:

MONGO_URI = "your-mongodb-connection-string"
JWT_SECRET = "your-secret-key"
RAZORPAY_KEY = "your-razorpay-key"
STRIPE_SECRET = "your-stripe-secret-key"

Start the backend server:

npm start

### 3. Frontend Setup
Navigate to the frontend directory:  cd frontend

Install dependencies:  npm install

Start the React frontend:  npm run dev

🚀 Future Enhancements
📱 Mobile App (React Native)
🎥 Video Consultations
📊 AI-based Doctor Recommendations
🏥 Integration with Hospitals

👨‍💻 Author
Developed by Anand Soni & Riya Lodha
📧 Email: anandsoni8621@gmail.com
📧 Email: riyalodha1802@gmail.com
📍 JECRC University, Jaipur

⭐ Don’t Forget to Give a Star!
If you find this project useful, don’t forget to give it a star ⭐ on GitHub! Your support helps the project grow and motivates the developers.

💡 Contributing
We welcome contributions! Feel free to fork the repository, create a branch, and submit a pull request. For bug fixes and feature requests, please use the issue tracker.

📝 License
This project is open-source and free to use under the MIT License.
