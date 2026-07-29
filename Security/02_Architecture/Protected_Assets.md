# Protected Assets Register

**Project:** AI Learning OS

**Document Owner:** Isaac

**Version:** 1.0

---

# Purpose

This document identifies the information assets that require protection and defines their security classification.

---

| ID | Asset | Description | Classification | CIA Priority |
|----|-------|-------------|----------------|--------------|
| A001 | Learning Goals | User learning objectives | Confidential | C, I |
| A002 | AI Roadmaps | Personalized learning plans | Confidential | C, I |
| A003 | Lessons | AI-generated educational content | Internal | I |
| A004 | Exercises | Assessment questions and answers | Internal | I |
| A005 | Feedback | AI evaluation results | Confidential | C, I |
| A006 | Progress Records | User progress and achievements | Confidential | C, I |
| A007 | REST API | Backend communication endpoints | Restricted | C, I, A |
| A008 | LLM API Key | Authentication key for AI services | Highly Confidential | C |
| A009 | Environment Variables | Configuration secrets | Highly Confidential | C |
| A010 | Source Code | Application source code | Restricted | C, I |

---

# CIA Classification

C = Confidentiality

I = Integrity

A = Availability

---

# Highest Value Assets

- API Keys
- Environment Variables
- User Progress
- Learning Goals
- REST API
- AI Responses

---

# Notes

This register will expand as the project evolves.