# AI Resume Analyzer & Interview Preparation Platform

An AI-powered MERN stack web application that analyzes a user's resume or self-description against a target job description.  
The platform provides:

- Resume-to-job match score
- Skill gap analysis
- Technical interview questions
- Behavioral interview questions
- Personalized 5-day learning roadmap

This project helps users prepare for job applications and interviews in a smarter and more structured way.

---

# Features

## Resume / Self Description Upload
- Upload resume in PDF format
- Option to provide self-description manually
- Extracts and analyzes user profile data

## Job Description Analysis
- Accepts target job description
- Compares candidate profile with required skills

## AI-Powered Evaluation
- Calculates resume-job matching score
- Detects missing skills and weaknesses
- Generates detailed feedback

## Interview Preparation
- Technical interview questions based on target role
- Behavioral interview questions
- Personalized preparation suggestions

## 5-Day Learning Roadmap
- Day-wise preparation plan
- Focused learning recommendations
- Helps bridge skill gaps quickly

## Skill Gap Detection
- Identifies missing technologies and concepts
- Suggests improvement areas

---

# Tech Stack

## Frontend
- React.js
- Context API
- Axios
- SCSS

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

## AI Integration
- Gemini API

## Other Tools
- PDF Parser
- Multer (file upload)
- JWT Authentication

---

# Project Structure

```bash
project-root/
│
├── client/                 # Frontend
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── services/
│
├── server/                 # Backend
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── services/
│   └── utils/
│
├── README.md
└── package.json
