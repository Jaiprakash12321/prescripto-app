Healthcare Portal - MERN Stack Application
A full-stack healthcare management platform connecting patients, doctors, and administrators

✨ Key Features
Patients
User registration/login with JWT authentication

Doctor search and profile viewing

Appointment booking with real-time availability

Online payments (Stripe/RazorPay)

Appointment management (view/cancel/reschedule)

Doctors
Dashboard with appointment calendar

Profile management

Appointment status management

Patient history viewing

Administrators
Full dashboard with analytics

Doctor management 

Appointment oversight

User management system

🛠 Tech Stack
Frontend:

React.js, Tailwind CSS, Redux Toolkit

Backend:

Node.js, Express.js, MongoDB

Integrations:

JWT Authentication, Stripe/RazorPay, Mongoose ODM

🚀 Quick Start
Clone repo:

bash
git clone https://github.com/your-username/healthcare-portal.git   
Install dependencies:

bash
# Frontend  
cd client && npm install  

# Backend  
cd ../server && npm install  
Configure environment:
Create .env files in client and server with:


bash
# Start backend  

# Start frontend  
cd ../client && npm start  
📂 Project Structure
text
healthcare-portal/  
├── client/           # React frontend  
│   ├── src/  
│   │   ├── components/  
│   │   ├── pages/    # Patient/Doctor/Admin views  
│   │   └── ...  
│  
├── server/           # Express backend  
│   ├── controllers/  
│   ├── models/       # MongoDB schemas  
│   ├── routes/       # API endpoints  
│   └── ...  
🔒 Authentication Flow
User registers with email/password

Server issues JWT token

Role-based access to features:

Patients: Book appointments

Doctors: Manage schedule

Admins: Manage system

💳 Payment Integration
Secure payment processing via Stripe/RazorPay

Payment records stored in database

Automatic confirmation emails



![image](https://github.com/user-attachments/assets/89ebe6ed-6f3e-4755-8ceb-fa904824d51c)
