# Application Inventory

**Project Name:** AI Learning OS

**Version:** MVP

**Application Security Lead:** <Isaac Gamah>

**Date:** 29 July 2026

---

# 1. Project Overview

AI Learning OS is an AI-powered learning platform designed to generate personalized learning roadmaps, lessons, exercises, feedback, and progress tracking for learners.

---

# 2. Architecture Overview

| Layer | Technology | Status |
|--------|------------|--------|
| Frontend | Next.js (App Router) | Confirmed |
| Backend | FastAPI | Confirmed |
| Styling | Tailwind CSS | Confirmed |
| UI Components | shadcn/ui | Confirmed |
| AI Engine | Large Language Model (LLM) | Confirmed |
| Database | TBD | Pending |
| Authentication | None (MVP) | Pending |
| Hosting | TBD | Pending |

---

# 3. Primary Users

- Student (MVP)

Future Users

- Instructor
- Administrator

---

# 4. Major Components

- Goal Input
- Roadmap Generator
- Lesson Generator
- Exercise Generator
- AI Feedback
- Progress Dashboard

---

# 5. Security Classification

| Asset | Classification |
|---------|----------------|
| Learning Goals | Confidential |
| Lessons | Internal |
| Exercises | Internal |
| AI Responses | Confidential |
| Progress Data | Confidential |
| API Endpoints | Restricted |
| API Keys | Highly Confidential |

---

# 6. Current Security Assumptions

- HTTPS will be used.
- Authentication will be introduced in future releases.
- AI responses must be validated before presentation.
- Sensitive information must never be exposed to users.

---

# Document Status

Draft Version 1.0