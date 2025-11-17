<div align="center">
  <br />
    <img src="public/readme/hero.webp" alt="Project Banner">
  <br />

  <div>
    <img alt="Static Badge" src="https://img.shields.io/badge/React-4c84f3?style=for-the-badge&logo=react&logoColor=white">
    <img src="https://img.shields.io/badge/-Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logo=typescript&logoColor=white&color=3178C6" />
    <img alt="Static Badge" src="https://img.shields.io/badge/Puter.js-181758?style=for-the-badge&logoColor=white">
  </div>

  <h3 align="center">AI Resume Analyzer</h3>

  <div align="center">
    A modern React-based project that analyzes resumes using built-in AI tools and cloud functionality.
  </div>
</div>

---

## 📋 Table of Contents
1. ✨ [Introduction](#introduction)  
2. ⚙️ [Tech Stack](#tech-stack)  
3. 🔋 [Features](#features)  
4. 🤸 [Getting Started](#quick-start)  
5. 🔗 [Assets](#links)  
6. 🚀 [Additional Info](#more)

---

## ✨ <a name="introduction">Introduction</a>

This project is an **AI-powered Resume Analyzer** built with React, TypeScript, Tailwind CSS, and Puter.js.  
It allows users to upload resumes, store them securely, and instantly receive AI-driven insights such as ATS scoring, job-match evaluations, and tailored feedback.

The goal behind building this app was to explore:

- AI integrations without a traditional backend  
- Modern state management  
- Clean and reusable UI components  
- File upload, storage, and retrieval inside the browser  

Although inspired by online resources, the project has been structured and personalized with my own customizations and improvements.

---

## ⚙️ <a name="tech-stack">Tech Stack</a>

### **Main Frameworks & Libraries**
- **React** — Component-based UI development
- **React Router v7** — Smooth client-side navigation
- **Tailwind CSS** — Utility-first styling
- **TypeScript** — Type-safe JavaScript

### **Cloud & AI**
- **Puter.js** — Handles browser-side auth, file storage, DB access, and AI (GPT, Claude, DALL·E, OCR, etc.)

### **Build Tools & State Management**
- **Vite** — Fast bundler & dev environment  
- **Zustand** — Lightweight global state system  

---

## 🔋 <a name="features">Features</a>

✔ **Browser-based Authentication**  
Simple, client-side login and session handling using Puter.js.

✔ **Resume Uploading & Secure Storage**  
Users can upload multiple resumes and store them directly in their Puter cloud environment.

✔ **AI-Generated Feedback & ATS Score**  
The app evaluates resumes based on any job description and provides:
- ATS ranking  
- Detailed feedback  
- Key strengths & weaknesses  

✔ **Clean & Reusable UI Components**  
Created with Tailwind CSS and modular file structuring.

✔ **Fast, Responsive, and Mobile-Friendly**  
Optimized layout that adapts to all devices.

✔ **Modular Codebase**  
Easy to extend, add new pages, and integrate more AI tools.

---

## 🤸 <a name="quick-start">Getting Started</a>

Follow the steps below to run the project locally:

### **1. Clone the Repository**
```bash
git clone <your-repo-url>
cd <project-folder>
```
### **2. Install Dependencies**

```
npm install
```

### **3. Start the Development Server**

```
npm run dev

```
#### **The project will be available at**
```
http://localhost:5173/
```