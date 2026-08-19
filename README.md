# Hi there 

# PA ji

**AI-powered personal assistant for law students and law graduates.**
*Law school, sorted, ji.*

PA ji helps students navigate the legal journey — legal research, case law exploration, moot court prep, drafting, and exam study — grounded in real, verifiable case law rather than AI-invented citations.

---

## What I'm building

**Problem**
Law students juggle moot court prep, dense casework, and exam pressure with tools that aren't built for the way legal study actually works. General-purpose AI tools are useful but risky for legal work — they can invent citations that don't exist, which is a non-starter in a field where every claim needs a real source.

**Solution**
PA ji is a study and research companion built specifically for law students, with every case citation cross-checked against real, retrieved case law (IndianKanoon, plus cases sourced directly from Supreme Court and High Court websites) — unverified citations are flagged, never presented as fact.

**Target users**
Primarily law students and recent law graduates, with judicial aspirants, legal interns, and young lawyers as a secondary audience.

**Current stage**
Live and in active development. Two features have launched: **War Room** and **Study Buddy**. Built after talking to 40+ law students and 20+ lawyers to validate the problem.

Try it live: [pa-ji-ai.streamlit.app](https://pa-ji-ai.streamlit.app/)

---

## Features

- **War Room** — Pressure-tests moot court arguments with opposing counsel arguments, rebuttals, and bench questions, across balanced, aggressive, and concessive styles. Every case citation is cross-checked against real case law and flagged if unverified.
- **Draft Generator** — Drafts for moot court and legal writing, including a full Memorial Generator: cover page, table of contents, index of authorities, statement of facts, arguments, and prayer — output as a formatted document.
- **Research & Analysis** — Analyzes legal documents.
- **Study Buddy** — A study companion with flashcards, mind maps, notes-grounded chat, exam-focused summaries, MCQ quizzes, answer-sheet grading against real exam questions, and practice Q&A from any uploaded source material.

> PA ji is research and study assistance only — not a substitute for legal advice, and not a replacement for your professor.

---

## Tech stack

- Python
- Streamlit
- Google authentication
- Google Analytics
- Legal database integrations (IndianKanoon + SC and HC court sources)

## Current development

- ✅ Authentication implemented
- ✅ Lead capture implemented
- ✅ Analytics integrated
- ✅ Testing infrastructure
- ✅ War Room — live
- ✅ Study Buddy — live
- 🚧 Draft Generator & Research/Analysis — in progress

---

## Team

Built by an engineering student. I leads backend/product, UI/UX, brand, and marketing.

---

*This is a public overview repo. The full product codebase is private during active development — reach out if you'd like a closer look.*
