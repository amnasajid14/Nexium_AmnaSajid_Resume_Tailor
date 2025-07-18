# Resume Tailor - Product Requirements Document (PRD)

## 🎯 Project Overview
**Resume Tailor** is an AI-powered web app that allows users to upload or paste their resume and input a specific job description. The app then tailors the resume using AI (via n8n + OpenAI or similar) to better match the job description.

## 👤 Target Users
- Job seekers
- Students and recent graduates
- Professionals applying for specific roles

## 🌟 Core Features
1. **Magic Link Authentication** (Email login – passwordless)
2. **Upload or Paste Resume** input field
3. **Paste Job Description** input field
4. **AI-powered Resume Tailoring**
   - Highlights keywords
   - Suggests or rewrites content to match job description
5. **Download Tailored Resume** (PDF/Word)
6. **Save Tailored Versions** (user dashboard with version history)

## 🧭 User Flow / Journey
1. User lands on homepage
2. Clicks "Login" → Enters email → Gets magic link → Authenticated
3. Uploads resume or pastes resume text
4. Pastes job description
5. Clicks “Tailor Resume”
6. Waits for AI to process → sees the improved version
7. User can download it or save it to their dashboard

## 🔧 Tech Stack
- **Frontend:** HTML/CSS/React
- **Backend:** Supabase (auth), MongoDB (resume storage)
- **AI Logic:** n8n + OpenAI API
- **Deployment:** Vercel with CI/CD
