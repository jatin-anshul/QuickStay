# 🏨 QuickStay  
## Full-Stack Hotel Management & Booking Platform

QuickStay is a production-ready **full-stack hotel booking and management web application**.

It allows users to browse hotels, check availability, book rooms, and make secure payments, while hotel owners can manage rooms, pricing, bookings, and revenue through a dedicated admin panel.

---

## 📌 Problem Statement

- Manual hotel booking systems are inefficient and error-prone
- Hotel owners lack centralized control over pricing and availability
- Secure authentication and payment handling is complex
- Booking confirmations often require manual communication

---

## 🚀 Features

### User Features

- Browse hotels and rooms
- Check real-time room availability
- Book rooms seamlessly
- Secure payments using **Stripe**
- Authentication via **Clerk**
- Receive booking confirmation emails
- View personal booking history

### Admin (Hotel Owner) Features

- Dedicated admin dashboard
- List hotels and rooms
- Upload hotel and room images
- Update room pricing
- Toggle room availability
- View current and past bookings
- Track total revenue and booking statistics

---

## 🧠 Technical Highlights

- Built RESTful APIs using Node.js and Express
- Implemented role-based access control (users and admins)
- Integrated Stripe Checkout and Webhooks for payments
- Used Clerk Authentication and Webhooks
- Automated booking confirmation emails using Nodemailer
- Managed image uploads using Cloudinary
- Deployed full-stack application on Vercel

---

## 🛠 Tech Stack

### Frontend

- React (Vite)
- Tailwind CSS
- Clerk Authentication
- Stripe Checkout

### Backend

- Node.js
- Express.js
- MongoDB with Mongoose
- Stripe Webhooks
- Clerk Webhooks
- Cloudinary
- Nodemailer

### Deployment

- Frontend: Vercel
- Backend: Vercel
- Database: MongoDB Atlas

---

## 🌐 Live Demo

- Frontend:  
  https://quick-stay-full-stack-qa9g.vercel.app/

- Backend:  
  https://quick-stay-full-stack-tan.vercel.app/

---

## 📸 Screenshots

### User Interface

<img width="1896" height="985" alt="image" src="https://github.com/user-attachments/assets/7829488d-2e21-444a-8d21-f74989ae8ec0" />

<img width="1919" height="977" alt="image" src="https://github.com/user-attachments/assets/a594cd0b-2ff5-49a2-a7d1-a0aa659fcc3a" />

<img width="1915" height="885" alt="image" src="https://github.com/user-attachments/assets/56080f7a-70c2-4e14-b4ae-0b702ead6d92" />

<img width="1914" height="979" alt="image" src="https://github.com/user-attachments/assets/c3b6d241-0992-4c2b-96f0-5a1017e3a83b" />

<img width="1749" height="889" alt="image" src="https://github.com/user-attachments/assets/55daff01-5ad9-4dfe-a2ca-c28d5a91b851" />

<img width="1396" height="955" alt="image" src="https://github.com/user-attachments/assets/78c64f8c-9610-49cc-9a0e-f797f9b71ccf" />

### Admin Panel

<img width="1432" height="976" alt="image" src="https://github.com/user-attachments/assets/7d6974b2-c5c1-4571-9ffc-74c287269753" />

<img width="1399" height="981" alt="image" src="https://github.com/user-attachments/assets/82593e7e-6b33-4f46-a89f-a58b5568d58a" />

<img width="1914" height="979" alt="image" src="https://github.com/user-attachments/assets/871af9a7-4cd2-4da0-ac2a-dbcec32ea030" />

---

## 🔐 Authentication, Payments & Emails

- Authentication handled using Clerk
- Payments processed via Stripe Checkout
- Booking confirmation emails sent using Nodemailer
- Secure webhook handling for Stripe and Clerk

---

## ⚙️ Setup & Installation

### Clone Repository

[git clone https://github.com/jatin-anshul/QuickStay.git]
cd QuickStay


### Frontend Setup 

- Create .env file inside client folder
VITE_CURRENCY=$
VITE_BACKEND_URL=http://localhost:5000
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

- Then run these commands in the terminal 
cd client
npm install
npm run dev

### Backend Setup

### Create .env file inside server folder

MONGODB_URI=your_mongodb_uri

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CLERK_WEBHOOK_SECRET=your_clerk_webhook_secret

STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret

SENDER_EMAIL=your_email
SMTP_USER=your_smtp_user
SMTP_PASS=your_smtp_password

### Then run these commands in the terminal

cd server

npm install

npm run server

---

## 🌐 Live Demo

Frontend: https://quick-stay-full-stack-qa9g.vercel.app/

Backend: https://quick-stay-full-stack-tan.vercel.app/

---

## 📦 Future Improvements

Reviews & ratings system

Advanced search & filters

Revenue analytics charts

Invoice generation

Multi-admin support

---

## 👨‍💻 Developer

Jatin Kumar 
Aspiring Full-Stack Web Developer
GitHub: https://github.com/jatin-anshul


---
