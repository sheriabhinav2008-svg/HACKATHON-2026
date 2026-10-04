# AI Placement Coach — HACKATHON-2026

## Problem
Students preparing for placements often use separate resources for aptitude, coding, CS fundamentals and interviews. Progress is fragmented, weak areas are hard to identify, and interview practice is inconsistent.

## Solution
**AI Placement Coach** is a browser-based placement preparation workspace that combines:
- Topic-wise Aptitude, DSA, DBMS and OOP/Java practice
- Instant answer feedback
- Accuracy and progress tracking using browser storage
- Java, DSA and HR interview practice
- A readiness score and skill-level view
- Coach insights that suggest what to focus on next

## Demo
This version is a **frontend prototype** designed for a hackathon presentation. It works without a backend or API key.

> Important: the current interview coach uses rule-based demo responses. It should not be presented as a live generative-AI model yet. A secure backend/LLM can be connected in the next phase.

## Run locally
Open `index.html` in a modern browser.

## Architecture
```
Student
   ↓
Placement Coach UI
   ├── Practice Engine → Question Bank → Score/Accuracy
   ├── Interview Coach → Prompt/Answer Flow
   └── Readiness Layer → Progress + Skill Insights
                 ↓
        Future secure AI backend
```

## Hackathon roadmap
1. Connect a secure AI backend for dynamic interview questions and feedback.
2. Add resume upload and resume-based interview generation.
3. Add adaptive question difficulty based on performance.
4. Add a personalized weekly study plan.
5. Add a backend database for accounts, history and leaderboards.

## GitHub Pages
The repository includes a GitHub Pages workflow. After Pages is enabled for **GitHub Actions** in the repository settings, the expected site address is:

`https://sheriabhinav2008-svg.github.io/HACKATHON-2026/`

## Repository
https://github.com/sheriabhinav2008-svg/HACKATHON-2026

Built for HACKATHON-2026.