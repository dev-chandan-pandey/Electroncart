# 🛒 Electroncart

**Electroncart** is a full-stack e-commerce web application built using the **MERN stack**. It provides users with a modern, responsive shopping experience featuring secure authentication, product management, cart functionality, and Razorpay payment integration.

## 🚀 Live Demo
🔗 [Electroncart Live](https://electroncart.vercel.app/)  
💻 [GitHub Repository](https://github.com/dev-chandan-pandey/Electroncart)

---

## 🧩 Features
- 🛍️ Full-featured e-commerce platform with product search, filter, and checkout.
- 🔐 Secure user authentication using **JWT** and **HTTP-only cookies**.
- 🧾 RESTful APIs for users, products, orders, and shipping management.
- 💳 Integrated **Razorpay** payment gateway for real-time transactions.
- ⚛️ Responsive frontend built with **React.js** and **Context API**.
- ☁️ Deployed on **Vercel** with optimized performance.

---

## 🛠️ Tech Stack
**Frontend:** React.js, Context API, HTML5, CSS3  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Payment Gateway:** Razorpay  
**Deployment:** Vercel  
**Authentication:** JWT, Cookies  

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/dev-chandan-pandey/Electroncart.git
   cd Electroncart
  ```
2. Install dependencies
```npm install
cd client && npm install
```
3. Add environment variables
Create a .env file in the root with the following keys:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret
RAZORPAY_KEY=your_razorpay_key
RAZORPAY_SECRET=your_razorpay_secret
```
4. Run the app
```
npm run dev
```
