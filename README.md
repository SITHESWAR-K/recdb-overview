# RECDB

RECDB is a student-built academic hub for Rajalakshmi Engineering College. It centralizes subject materials, previous question papers, an AI study assistant, a browser code editor, and a contributor leaderboard in one web app.

This project is designed as a real-world portfolio piece: it combines a React frontend, Firebase services, and a secure Express backend with rate limiting, token verification, and AI integration.

Live site: https://rec-db-official.web.app/

## What This Project Solves

Students usually keep notes, question papers, syllabus links, and revision resources in separate places. RECDB brings those resources together in one searchable platform and adds tools that make revision faster:

- browse subjects by department and search by subject code or name
- open unit-wise study material, syllabus, and exam resources
- ask REC AI for explanations, summaries, and exam-style help
- use the embedded code editor for programming practice
- track contributor rankings through the leaderboard
- show live visitor and usage statistics

## Key Features

- Subject directory with department filters, search, and pagination
- Subject detail pages with syllabus, unit resources, and question paper links
- REC AI chat assistant for academic support
- Code editor embedded through OneCompiler
- Contributor leaderboard with points-based recognition
- Live visitor stats powered by Firebase Realtime Database
- Anonymous authentication for browsing protected features
- SEO-friendly metadata, canonical URLs, and sitemap generation
- Mobile-friendly UI with route-based lazy loading and error boundaries

## Tech Stack

Frontend:

- React 19
- Vite
- React Router
- React Helmet Async
- Firebase client SDK
- MUI, React Icons, React Markdown, Syntax Highlighter

Backend and services:

- Express
- Firebase Admin SDK
- Firebase Firestore, Storage, Auth, and Realtime Database
- Zoho Catalyst / Appsail backend hosting
- Groq-compatible OpenAI API for REC AI
- Nodemailer for email notifications
- Multer and express-rate-limit for upload and abuse protection

## Main User Flows

### 1. Browse study materials

Users can open the subject directory, filter by department, search for subjects, and view subject-specific resources such as syllabus, unit notes, CAT papers, and semester papers.

### 2. Ask REC AI

REC AI is a chat assistant built for study support. The frontend sends a protected request with the current conversation context, and the backend uses an AI model to generate a concise academic response.

### 3. Contribute content

Students can submit notes and question papers through the contribution flow. Contributions are tracked on the leaderboard and scored using a point system.

### 4. Use the code editor

The code editor page embeds OneCompiler so students can practice programming without leaving the app.

## Recruiter Summary

RECDB shows practical experience across frontend, backend, cloud services, and product thinking. The project demonstrates:

- building a routed React app with lazy loading and guarded flows
- integrating Firebase Authentication, Firestore, Storage, and Realtime Database
- designing a secure Express API with token checks and rate limiting
- connecting a frontend chat experience to an AI backend
- adding SEO, sitemap generation, and metadata for discoverability
- turning a college need into a usable student platform

## Note

- The project is a student-built academic platform and is not the official Rajalakshmi Engineering College website.
