🩺 DOCTOR APPOINTMENT SYSTEM

A full-stack Doctor Appointment Booking System that allows patients to book appointments, doctors to manage schedules, and admins to control the platform.

⚙️ INSTALL NODE.JS

(Ignore if already installed)

Visit the official Node.js website
👉 https://nodejs.org/en/download/

Download the Node.js installer

Run the installer

Follow the prompts in the installer

⚠️ IMPORTANT NOTE

First Run Backend → Then Frontend & Admin Panel

🛠️ BACKEND SETUP
Steps To Setup Backend Of The Project

Open the project folder in VS Code

Open Integrated Terminal

Right click on backend

Select “Open in Integrated Terminal”

Install dependencies:

npm install


(Requires internet connection)

☁️ CLOUDINARY SETUP (File Storage)

Create an account and login
👉 https://cloudinary.com/

Go to Dashboard

Copy the following:

Cloud Name

API Key

API Secret

Paste them into:

backend/.env

🗄️ MONGODB SETUP

Open MongoDB Atlas
👉 https://www.mongodb.com/cloud/atlas

Sign up / Login

Click New Project

Go to Database → Build a Database

Select M0 (Free Tier) & choose your region

Create a Username & Password
⚠️ Do not use @ symbol in password

Click Finish & Close

Whitelist IP:

0.0.0.0/0


Click Connect

Select Compass Option

Copy the Connection String

Paste it into:

backend/.env


Replace <password> with your database password

❌ Do NOT add / at the end of MongoDB URI

💳 STRIPE SETUP (Optional)

Create account
👉 https://stripe.com/

Get Stripe Secret Key from dashboard

Paste it into:

backend/.env

💰 RAZORPAY SETUP (Optional)

Create account
👉 https://razorpay.com/

Get:

Razorpay Key ID

Razorpay Secret Key

Paste both into:

backend/.env

▶️ RUN BACKEND
npm run server


✅ Make sure backend is running before starting frontend or admin

💻 FRONTEND SETUP
Steps To Run Frontend

Right click on frontend folder
→ Select Open in Integrated Terminal

Install dependencies:

npm install


Start frontend:

npm run dev


Open in browser:

http://localhost:5173

🧑‍⚕️ ADMIN PANEL SETUP
Steps To Run Admin Panel

Right click on admin folder
→ Select Open in Integrated Terminal

Install dependencies:

npm install


Start admin panel:

npm run dev


Open in browser:

http://localhost:5174

✨ FEATURES

Patient Appointment Booking

Doctor Schedule Management

Admin Dashboard

Secure Authentication

File Upload (Cloudinary)

Online Payments (Stripe / Razorpay)

MongoDB Database

🚀 DEPLOYMENT

Backend: Vercel / Render

Frontend: Vercel

Admin Panel: Vercel

Environment variables must be added before deployment
