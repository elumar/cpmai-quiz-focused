# 📘 CPMAI Exam Study Hub

> A self-directed study platform built to prepare for the **PMI Certified in AI** 
> (CPMAI) certification exam — featuring an interactive quiz engine, 
> phase-by-phase video breakdowns, and deep-dive podcast sessions.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue?style=for-the-badge)](YOUR_GITHUB_PAGES_URL)
[![YouTube Playlist](https://img.shields.io/badge/YouTube-Phase%20Videos-red?style=for-the-badge&logo=youtube)](YOUR_YOUTUBE_PLAYLIST_URL)

---

## 🎯 Purpose

The PMI-CPMAI exam tests your ability to apply the full CRISP-DM-inspired 
cognitive AI project lifecycle — from Phase I Business Understanding through 
Phase VI Model Operationalization. Generic study materials are scarce.

This hub exists to fill that gap with:
- **Scenario-based practice questions** that mirror the style, depth, and 
  traps of the actual exam
- **Video walkthroughs** that give you an 8-minute mental map of each phase
- **Podcast-style deep dives** *(coming soon)* that unpack every task group 
  and task at exam depth

---

## ✨ Features

### 🧠 Interactive Quiz Engine
- **XX scenario-based questions** organized by phase, task group, and task
- Questions generated with **DeepSeek AI** and quality-audited with **Claude** 
  against a strict PMI-CPMAI outline
- Each question includes a full explanation covering *why* the correct answer 
  is right and *why each distractor is wrong* — not just a restatement of 
  the answer
- Answer distribution is balanced across all four option positions to 
  eliminate length-bias and position-bias test-taking shortcuts

### 📋 Quality Standards Applied to Every Question
Every question in this bank was evaluated against a structured QA framework:
- **Structural audit** — CSV integrity, answer distribution balance, option 
  length parity
- **Content audit** — scenario-based framing, distractor plausibility, 
  correct-answer accuracy, concept coverage
- **Traceability** — every explanation includes a `[Maps to: Phase – Task 
  Group – Task]` tag anchored to the official PMI-CPMAI outline

---

## 📺 Companion Video Series

Each CPMAI phase has a dedicated **8-minute overview video** on YouTube 
covering:
- Phase objectives and key deliverables
- Common **exam traps** and how to avoid them
- **Memory hooks** for locking in phase-specific terminology

▶️ [Watch the full playlist →](YOUR_YOUTUBE_PLAYLIST_URL)

---

## 🎙️ Podcast Series *(Coming Soon)*

A more in-depth companion audio series for each phase, covering:
- Every **task group** and **task** in the CPMAI outline
- How tasks connect across phases
- Real-world AI project scenarios mapped to CPMAI concepts

Available on YouTube shortly.

---

## 🛠️ How It Was Built

| Component | Tool |
|---|---|
| Quiz page & UI | Claude (Anthropic) |
| Question generation | DeepSeek AI |
| Question QA & audit | Claude (Anthropic) |
| Hosting | GitHub Pages |

Claude was used throughout the question development process because of its 
ability to apply strict guardrails — enforcing official phase names, 
rejecting invented PMI policies, flagging answer-key bias, and ensuring 
every explanation teaches a principle rather than restating the answer.

---

## 🗂️ Project Structure
```
cpmai-quiz-focused/
├── index.html          # Main quiz interface
├── questions/          # Question bank (CSV/JSON)
├── assets/             # Styles, scripts, images
└── README.md
```

---

## 🚀 Getting Started

No installation required. Access the live site at:

**[YOUR_GITHUB_PAGES_URL](YOUR_GITHUB_PAGES_URL)**

To run locally:
1. Clone this repository
2. Open `index.html` in your browser
3. No build step required

---

## 📖 About the PMI-CPMAI Exam

The **PMI Certified in Artificial Intelligence (CPMAI)** certification 
validates your ability to lead and manage AI/ML projects using a structured 
cognitive project methodology. It covers six lifecycle phases:

| Phase | Name |
|---|---|
| Phase I | Business Understanding |
| Phase II | Data Understanding |
| Phase III | Data Preparation |
| Phase IV | Model Development |
| Phase V | Model Evaluation |
| Phase VI | Model Operationalization |

Learn more at [pmi.org](https://www.pmi.org).

---

## 📌 Roadmap

- [x] Phase VI quiz questions (live)
- [ ] Phases I–V quiz questions
- [ ] Podcast audio series on YouTube
- [ ] Progress tracking / score history
- [ ] Timed exam simulation mode

---

## 👤 Author

**Elumar** — PMI-PMP | MBA | PMI-CPMAI Candidate  
Building this while studying, so the resource grows with the journey.

---

## 📄 License

[MIT](LICENSE) — free to use and adapt for your own study purposes. 
Attribution appreciated but not required.
