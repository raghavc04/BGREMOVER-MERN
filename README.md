# 🖼️ Background Remover - MERN Stack

## 📌 Project Description  
Background Remover is a **MERN Stack-based web application** that allows users to upload images and remove their backgrounds using AI-powered APIs. It includes **user authentication** via Clerk and **backend API integration** with ClipDrop.

---

## 🚀 Technologies Used  
- **Frontend:** Vite + React.js  
- **Backend:** Node.js + Express.js  
- **Database:** MongoDB (Mongoose)  
- **Authentication:** Clerk  
- **API Integration:** ClipDrop API  

---

## 📂 Project Structure  
/BGREMOVER-MERN 
│── /client (Frontend - Vite + React) 
│── /server (Backend - Node + Express) 


---

## ⚙️ Setup and Installation  

### **1️⃣ Clone the Repository**  

git clone https://github.com/raghavc04/BGREMOVER-MERN.git
cd BGREMOVER-MERN


2️⃣ Install Dependencies
🔹 Backend (Server)
cd server
npm install

🔹Frontend (Client)
cd client
npm install

3️⃣ Configure Environment Variables
VITE_CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key
VITE_BACKEND_URL=http://localhost:4000

📌 Note: Get your Clerk Publishable Key from Clerk Dashboard and replace your-clerk-publishable-key.

🔹 Server (server/.env)
PORT=4000

# MongoDB Setup ( required )
MONGODB_URI = '------ MongoDB URI here ------'

# CLERK_WEBHOOK ( required )
CLERK_WEBHOOK_SECRET = '------ Clerk Webhook Secret here ------'

# CLIPDROP API ( required )
CLIPDROP_API = '------ ClipDrop API Key here ------'

CURRENCY ='INR'

# Razorpay Payment Integration
RAZORPAY_KEY_ID = '------ Razorpay Key Id here ------'
RAZORPAY_KEY_SECRET = '------ Razorpay Key Secret here ------'

# Stripe Payment Integration
STRIPE_SECRET_KEY="------ Stripe Secret Key here ------"

📌 Note: Replace the placeholders with your MongoDB URI, ClipDrop API Key, and Clerk Webhook Secret.

4️⃣ Start the Application
🔹 Start Backend (Server)
cd server
npm run dev

🔹 Start Frontend (Client)
cd client
npm run dev

✨ Features
✔️ Remove image backgrounds using AI
✔️ User authentication via Clerk
✔️ API integration with ClipDrop
✔️ MERN stack implementation


📞 Contact
For any enquiries or more information, feel free to reach out at:
📩 raghavc2002@gmail.com
