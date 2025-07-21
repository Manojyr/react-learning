# react-learning
🛒 MERN Stack E-commerce App

This is a full-stack **E-commerce web application** built with the **MERN stack** (MongoDB, Express, React, Node.js). It supports user authentication, product listing, cart, checkout, and integrates **Weaviate** and **Google AI APIs** for enhanced functionality.

---

## 📦 Technologies Used

### 💻 Frontend:
- React.js
- Axios
- React Router
- Tailwind CSS / Bootstrap (optional)

### 🛠 Backend:
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT for Authentication
- Weaviate (Vector DB Integration)
- Google AI API (optional for smart features)

---

## 🚀 Features

- 🔐 User Authentication (JWT)
- 🛍 Product Listing & Categories
- ➕ Add to Cart / Remove from Cart
- 💳 Order Placement & Tracking
- 🧠 Crop Disease Detection (Image upload + AI API)
- 📦 Admin Panel (if included)
- 🔍 Weaviate integration for semantic product search

---

## 📁 Project Structure

MERN-Stack-Ecommerce-App-master/
├── backend/
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── utils/
│ ├── .env
│ └── index.js
├── client/
│ ├── src/
│ ├── public/
│ └── package.json
└── README.md

yaml
Copy code

---

## 🔧 Getting Started

### 1. Clone & Install

```bash
git clone https://github.com/yourusername/mern-ecommerce.git
cd mern-ecommerce
2. Backend Setup
bash
Copy code
cd backend
npm install
Create .env file in backend/:
env
Copy code
PORT=5000
MONGO_URI=mongodb://localhost:27017/ecommerce
JWT_SECRET=your_jwt_secret_key

WEAVIATE_HOST=https://your-weaviate-instance.weaviate.network
WEAVIATE_API_KEY=your_weaviate_api_key
GOOGLE_AI_API_KEY=your_google_api_key
Run Backend:
bash
Copy code
npm run sync-weaviate   # (optional, if using Weaviate)
npm run dev
3. Frontend Setup
bash
Copy code
cd ../client
npm install
npm start
Frontend runs at: http://localhost:3000
Backend runs at: http://localhost:5000

🧪 API Endpoints
Some example endpoints:

Method	Endpoint	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	Login user
GET	/api/products	Fetch all products
POST	/api/cart	Add to cart
POST	/api/detect-crop	Upload & detect disease

🌐 External APIs
Weaviate Cloud

Google Vertex AI / PaLM API

📸 Screenshots
(Add screenshots of your app here)

📄 License
This project is open-source under the MIT License.

👨‍💻 Author
Made with ❤️ by Manoj YR

yaml
Copy code

---

Let me know if you'd like me to:
- Tailor this for deployment (like Vercel + Render).
- Add API documentation or Postman collection.
- Include screenshots in the README.










