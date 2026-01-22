# 🎨 Thumblify – AI Thumbnail Generator

Thumblify is a powerful AI-driven web application that generates **high quality thumbnails**.  
Just describe your idea, choose a style, and let AI create eye-catching visuals for your content.

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![React](https://img.shields.io/badge/react-%2320232b.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

Perfect for **YouTubers, marketers, and content creators** who want professional thumbnails without design skills.

![Thumbnail](./Readme%20Assets/thumbnail.png) 
---
---
## 🌐 Live Demo & Repository

🔗 **Live Demo:** [Thumblify](https://thumblify-mauve.vercel.app)

🔗 **GitHub Repository:** [https://github.com/Sumit444-commits/Thumblify](https://github.com/Sumit444-commits/Thumblify)


---

## 📸 Preview

### Home
![Home](./Readme%20Assets/home.png)

### Generator Page
![Generator Page](./Readme%20Assets/generator.png)

### My Generations Page
![My Generations Page](./Readme%20Assets/my-generations.png)


---

## 🚀 Features

- **AI-Powered Generation** – Describe your topic and let AI bring it to life.
- **Customizable Styles** – Bold & Graphic, Minimalist, Photorealistic, and more.
- **Aspect Ratios** –  
  - YouTube: `16:9`  
  - Instagram: `1:1`  
  - TikTok / Shorts: `9:16`
- **Color Schemes** – Preset palettes for branding.
- **User Gallery** – View all your past generations.
- **Secure Authentication** – Session-based user accounts.
- **Fast & Responsive UI** – Built with Vite + Tailwind CSS.

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- Lucide React (Icons)

### Backend
- Node.js + Express
- MongoDB + Mongoose
- Express-Session
- Bytez.js (AI Models)
- Cloudinary (Image hosting)
- Zod (Validation)


### Deployment
- Vercel (Frontend + Serverless Backend)

---

## 📂 Project Structure

### Backend

backend/
├── controllers/ # Auth & generation logic

├── models/ # Mongoose schemas

├── routes/ # API routes

├── middleware/ # Auth & error handling

├── validate/ # Zod schemas

└── index.js

### Frontend

frontend/

├── src/

│ ├── pages/ # Home, Generator, My Generations

│ ├── components/ # Navbar, Footer, Inputs

│ ├── context/ # Session & global state

│ └── main.jsx



---

## ⚙️ Getting Started

### Prerequisites
- React JS
- Node.js **v18+**
- MongoDB Atlas account
- Bytez.js API Key

---

## 📥 Installation

### 1. Clone the repository
```bash
git clone https://github.com/Sumit444-commits/Thumblify.git

cd thumblify

2. Install dependencies
## Backend
cd backend
npm install

## Frontend
cd ../frontend
npm install

🔐 Environment Variables

Create a .env file in backend/

PORT=5000
MONGODB_URI=your_mongodb_connection_string
SESSION_KEY=your_secret_key
BYTEZ_API_KEY=your_bytez_key
CLOUDINARY_URL=CLOUDINARY_URL=cloudinary://<your_api_key>:<your_api_secret>@<your_cloud_name>
NODE_ENV="production"

Create a .env file in frontend/
VITE_BASE_URI=your_server_base_uri (e.g: "http://localhost:5000")


▶️ Run Locally
Backend

cd backend
npm start

Frontend

cd frontend
npm run dev

App will run at:

Frontend: http://localhost:5173
Backend: http://localhost:5000
```
---

🧠 How It Works

- User describes thumbnail idea
- Prompt sent to Bytez AI
- AI generates image
- Image uploaded to Cloudinary
- Saved to MongoDB
- Displayed in user gallery




# 👨‍💻  Author

## Sumit Sharma

🔗 **GitHub:** [Sumit444-commits](https://github.com/Sumit444-commits)
🔗 **LinkedIn:** [Sumit Sharma](https://www.linkedin.com/in/sumit-sharma-a0b2c7)
🔗 **Portfolio:** [https://www.sumitsharma.codes/](https://www.sumitsharma.codes/)