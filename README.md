# 🧠 Sensai – AI Career Coach  

**Sensai** is an intelligent career coaching platform that helps users elevate their professional journey with AI-powered tools — from crafting ATS-friendly resumes to preparing for interviews and discovering personalized career insights all in one place.

---

## 🚀 Features  

### 🔐 Authentication  
- Secure **login** and **logout** powered by **[Clerk](https://clerk.com/)**.  
- Smooth onboarding and session management for a seamless user experience.  

### 📄 AI Resume Builder  
- Create **ATS-friendly resumes** optimized for job applications.  
- Automatically formats and enhances content using **Gemini AI** for clarity and impact.  
- **Save and download your resume** in professional formats (PDF or DOCX) anytime.  

### 📨 AI Cover Letter Generator  
- Generate **personalized cover letters** tailored to job descriptions and resumes.  
- Fine-tuned tone and structure with AI assistance.  

### 🎯 Interview Preparation  
- Practice with **AI-generated quizzes and mock interview questions**.  
- Get feedback and improve your readiness for real interviews.  

### 💼 Personalized Insights & Recommendations  
- Receive **career and industry insights** tailored to your experience and goals.  
- AI-driven recommendations for skills, job roles, and career growth strategies.  

---

## 🧩 Tech Stack  

| Layer | Technology |
|-------|-------------|
| **Frontend Framework** | [Next.js](https://nextjs.org/) |
| **UI Components** | [shadcn/ui](https://ui.shadcn.com/) |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) |
| **Authentication** | [Clerk](https://clerk.com/) |
| **AI Integration** | [Gemini API](https://ai.google.dev/) |
| **Database** | [Neon](https://neon.tech/) (Serverless Postgres) |

---

## ⚙️ Getting Started  

```bash

### 1. Clone the repository
git clone https://github.com/yourusername/sensai-ai-career-coach.git
cd sensai-ai-career-coach

### 2. Install dependencies
npm install
# or
yarn install


3. Set up environment variables
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key=
CLERK_SECRET_KEY=your_clerk_secret=
DATABASE_URL=your_neon_database_url=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=
GEMINI_API_KEY=your_gemini_api_key=


4. Run the development server
npm run dev
# or
yarn dev
