# AI Resume Shortlisting & Job Portal

An AI-powered recruitment platform that streamlines the hiring process by automating resume analysis, ATS score generation, and candidate evaluation. The system enables candidates to upload resumes, receive AI-generated insights, and apply for jobs, while recruiters can efficiently manage job postings and evaluate applicants. An admin dashboard provides centralized management of users, recruiters, and job listings.

---

## 🚀 Features

### 👤 Candidate Module
- User Registration & Login
- Profile Management
- Upload Resume (PDF)
- AI-powered Resume Analysis
- ATS Score Generation
- AI-generated Resume Summary
- Search & Apply for Jobs
- Track Job Applications
- Personalized Dashboard

### 🏢 Recruiter Module
- Recruiter Registration & Login
- Company Profile Management
- Create, Update, and Delete Job Posts
- View Applicants
- AI-assisted Resume Evaluation
- ATS Score-Based Candidate Ranking
- Candidate Shortlisting
- Manage Applications

### 🛠️ Admin Module
- Secure Admin Login
- Manage Candidates
- Manage Recruiters
- Manage Job Listings
- Dashboard Analytics
- Platform Monitoring

---

## 🤖 AI Features

- PDF Resume Upload
- Resume Text Extraction using **pdf-parse**
- AI-powered Resume Analysis using **OpenAI API**
- ATS Score Generation
- Candidate Information Extraction
- AI-generated Resume Summary
- Resume-based Candidate Evaluation
- Intelligent Candidate Ranking

---

## 🛠️ Technology Stack

### Frontend
- React
- Vite
- Tailwind CSS
- React Router DOM
- Axios
- Lucide React

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- JWT (JSON Web Token)
- bcrypt.js

### Resume Processing
- Multer
- pdf-parse

### AI Integration
- OpenAI API

---

## 📊 System Workflow

```text
Candidate Registration/Login
          │
          ▼
      Upload Resume (PDF)
          │
          ▼
      Multer File Upload
          │
          ▼
   Resume Text Extraction
      using pdf-parse
          │
          ▼
     OpenAI API Analysis
          │
          ▼
Generate ATS Score & AI Summary
          │
          ▼
Extract Candidate Information
          │
          ▼
Apply for Jobs
          │
          ▼
Recruiter Reviews Applicants
          │
          ▼
Candidate Ranking & Shortlisting
```

---

## 📁 Project Structure

```text
AI_Resume_Shortlisting_Job_Portal/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── package.json
│   └── server.js
│
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Backend

```bash
cd backend
npm install
npm start
```

### Environment Variables

Create a `.env` file inside the `backend` directory.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key
```

---

## 🎯 Key Highlights

- AI-powered Resume Analysis
- ATS Score Generation
- Resume Text Extraction from PDF
- OpenAI API Integration
- Secure JWT Authentication
- Candidate, Recruiter, and Admin Dashboards
- Responsive User Interface
- RESTful API Architecture

---

## 👥 Team

- Prathyusha
- Shivarani
- Farzana

---

## 📄 License

This project was developed as an academic major project for educational purposes. It demonstrates the integration of Artificial Intelligence with modern web technologies to automate resume analysis, ATS scoring, and candidate shortlisting.
