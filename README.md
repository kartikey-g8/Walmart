🛍️ ShopSense — AI-Powered E-Commerce Platform

Walmart Sparkathon 2025 Submission

📺 Project Demo

▶️ Watch the full walkthrough on YouTube:
https://youtu.be/Fd24d0InHP8?si=q71ylUkppw7xnn5-
ShopSense – AI-Powered E-Commerce Platform (Walmart Sparkathon 2025)

🚀 Overview

ShopSense is a full-stack AI-driven e-commerce platform built on the MERN stack, designed to deliver a smarter, more intuitive, and personalized shopping experience.

Developed by ShopSense Squad for Walmart Sparkathon 2025, the platform integrates multiple AI capabilities to go beyond traditional online shopping.

✨ Key AI Features
🎙️ Voice Search

Hands-free product searching powered by Web Speech API and Voiceflow.
Users can simply speak to filter products by category.

📸 Image Search

Upload an image to find visually similar products.
Implemented using a Flask microservice with TensorFlow, NumPy, and Scikit-learn, extracting and comparing visual embeddings stored in MongoDB.

🧠 AI Wish List Recommendations

A collaborative filtering–based recommendation engine in Python that suggests complementary and trending products based on user behavior.

💬 AI Chatbot & Personalized Support

A Voiceflow-integrated chatbot that:

Handles FAQs

Guides users through the platform

Provides personalized product suggestions based on past interactions

🛒 Core Features

Dynamic Category Navigation (Men, Women, Furniture, Trending, etc.)

Detailed Product Pages with images, pricing, and related items

Seamless Checkout Flow with secure address collection and integrated payment gateway

Admin Dashboard for managing users, orders, and real-time status tracking

🛠️ Technical Stack
Frontend

Vite + React

Tailwind CSS

React Context API (state management)

Backend

Node.js

Express.js

MongoDB Atlas

AI Services

Flask microservice

TensorFlow, NumPy, Scikit-learn

PyMongo

Infrastructure

Static assets served via Cloudflare CDN

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/kartikey-g8/Walmart.git

2️⃣ Setup Frontend
cd client
npm install
npm run dev

3️⃣ Setup Backend
cd server
npm install
npm start

4️⃣ Run AI Services

Ensure the Flask environment is configured and running:

python app.py

👥 Contributors

ShopSense Squad
