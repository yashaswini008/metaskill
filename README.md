# 🚀 Metaskill 

This is featuring a full-stack job and networking portal with **AI-powered skill extraction** and **Web3 wallet-based job posting payments**.

---

## 🧰 Tech Stack

| Layer       | Technologies Used                                  |
|-------------|-----------------------------------------------------|
| Frontend    | React.js, Tailwind CSS                              |
| Backend     | Node.js, Express.js                                 |
| Database    | MongoDB                                             |
| AI/NLP      | OpenAI API (Skill extraction)                       |
| Web3        | MetaMask, Ethers.js (Ethereum testnet)              |
| Deployment  | Vercel (Frontend)                                   |

---

## ✨ Features

### 👤 Authentication & Profile
- User registration & login (JWT-based)
- Profile with name, bio, LinkedIn URL
- Manual or AI-extracted skills
- MetaMask wallet address connection

### 💼 Job Portal
- Authenticated job posting
- View job listings and user posts
- Filter by skills or tags
- Platform fee via MetaMask payment (testnet)

### 🧠 AI Features
- Extracts user skills from bio using OpenAI
- (Upcoming) Resume parsing and job matching logic

### 🌐 Web3 Integration
- MetaMask login and wallet connection
- Platform fee payment before job post
- Ethers.js integration with transaction confirmation

---

## 🧑‍💻 Developer

**Yashaswini Ande**  
📫 ande.yashaswini@gmail.com  
🔗 [GitHub Profile](https://github.com/yashaswini008)

---

## ⚙️ Local Setup Instructions

>  Note: Frontend is already deployed on Vercel. Backend runs locally.

### 1️ Backend
```bash
cd backend
npm install
npm start


