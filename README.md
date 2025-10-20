<!-- Banner -->
<p align="center">
  <img src="https://github.com/yourusername/sensai/blob/main/public/banner.png" alt="Sensai - The AI Career Coach" width="80%" />
</p>

<h1 align="center">🧠 Sensai – The AI Career Coach</h1>

<p align="center">
  <b>Sensai is an intelligent career coaching platform that helps users elevate their professional journey with AI-powered tools — from crafting ATS-friendly resumes to preparing for interviews and discovering personalized career insights all in one place.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Built%20With-Next.js-000000?style=for-the-badge&logo=nextdotjs" />
  <img src="https://img.shields.io/badge/UI-TailwindCSS-38B2AC?style=for-the-badge&logo=tailwindcss" />
  <img src="https://img.shields.io/badge/Auth-Clerk-FB542B?style=for-the-badge&logo=clerk" />
  <img src="https://img.shields.io/badge/AI-Gemini%20API-4285F4?style=for-the-badge&logo=google" />
  <img src="https://img.shields.io/badge/UI%20Components-shadcn%2Fui-111111?style=for-the-badge" />
</p>

---

## 🚀 Overview

**Sensai** is your personal **AI Career Coach** that simplifies your professional journey.  
With features like **resume building**, **interview quizzes**, and **AI-generated cover letters**, Sensai helps you prepare for success — faster and smarter.

---

## ✨ Features

### 🔐 Authentication
- Secure **Sign In / Sign Out** with [Clerk](https://clerk.dev/)
- Smooth session management and user profile handling

### 📄 ATS-Friendly Resume Builder
- Create beautiful, **ATS-optimized resumes** in minutes  
- Download in **PDF format** directly from the browser  
- Powered by intelligent resume templates

### 🧩 AI Interview Quiz
- Generate **custom 10-question quizzes** using **Gemini API**  
- Get **detailed performance reviews** and explanations  
- Train for both **technical** and **behavioral** interviews

### 📝 AI Cover Letter Creator
- Build **personalized, job-specific cover letters** instantly  
- Perfect grammar, tone, and formatting — powered by AI

---

## 🧰 Tech Stack

| Category | Technology |
|-----------|-------------|
| Frontend | **Next.js** |
| Styling | **Tailwind CSS**, **shadcn/ui**, **Framer Motion** |
| Authentication | **Clerk** |
| AI Engine | **Gemini API (Google AI)** |
| Icons | **Lucide Icons** |

---

## ⚙️ Installation & Setup

### 🪜 Steps

```bash
# 1️⃣ Clone the repository
git clone https://github.com/yourusername/sensai.git

# 2️⃣ Move into the project directory
cd sensai

# 3️⃣ Install dependencies
npm install

# 4️⃣ Create environment variables (see below)

# 5️⃣ Run the app
npm run dev




```
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```
