# Application Routes

**Project:** AI Learning OS

**Document Owner:** Isaac

**Version:** 1.0

---

# Purpose

This document identifies every accessible application route and its associated security considerations.

---

| Route | Function | Data Processed | Security Risks | Security Controls |
|--------|----------|----------------|----------------|-------------------|
| / | Goal Input | User learning goals | Prompt Injection, Input Validation | Validate input, sanitize data |
| /roadmap | Learning Roadmap | AI-generated roadmap | Unauthorized access | Authorization, secure API calls |
| /lesson/[moduleId] | Lesson View | AI lesson content | XSS, content manipulation | Output encoding, content validation |
| /exercise/[lessonId] | Exercise View | User answers | Injection, tampering | Server-side validation |
| /feedback | AI Feedback | Scores and recommendations | Data leakage | Secure API responses |
| /progress | Progress Dashboard | User progress | IDOR, unauthorized access | Authorization checks |

---

# External Interfaces

| Interface | Purpose | Security Concern |
|------------|---------|------------------|
| FastAPI REST API | Backend communication | Authentication, rate limiting |
| LLM API | AI-generated content | Prompt injection, information leakage |

---

# Security Review Notes

Every new route introduced into the application must undergo an Application Security Review before deployment.

---

# Status

Draft Version 1.0