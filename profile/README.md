# UniPrep 

UniPrep is a full-stack EdTech platform for CUET preparation. It combines a student learning system with an admin CMS, focusing on structured, data-driven exam preparation.

## 🎯 Aim
- Transform preparation from random studying → performance-driven learning
- Help students identify weak areas and improve systematically
- Provide a single platform for learning, practice, and analysis

## 💻 Technology Stack
- **Core**: Next.js (App Router), React, TypeScript
- **Styling**: Tailwind CSS, Styled-Components
- **Animations**: Motion, GSAP, Lenis
- **Backend**: Supabase
- **State Management**: Zustand
- **Other**: Axios, Server Actions, xlsx

## 🧩 Architecture
- Built on Next.js App Router (full-stack architecture)
- Frontend + Backend in single codebase
- API routes inside `/app/api`
- Middleware for authentication & route protection

## 👨‍🎓 Student Features
- **Mock Tests**: CUET-based, timed exams
- **Performance Analytics**: Score, accuracy, weak areas
- **Dashboard**: Track progress & attempts
- **Study Materials**: Notes, PDFs, syllabus coverage
- **Notices**: Updates, announcements
- **Profile**: User settings & preferences

## 🛠️ Admin CMS Features
- Secure admin dashboard
- Test creation & management
- Question & flashcard management
- Bulk upload via Excel (xlsx)
- Zustand stores for state handling

## 🔐 Security
- Authentication via Supabase + `@supabase/ssr`
- Middleware-based route protection
- Role-Based Access Control (RBAC)
- Only `is_admin: true` users access admin panel

## ⚡ Key Highlights
- Full-stack single codebase
- Real-time analytics & tracking
- Secure admin CMS
- Bulk data handling
- Smooth UI/UX with animations
- SEO optimized & publicly accessible
