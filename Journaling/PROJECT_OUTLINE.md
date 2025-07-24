# 🧠 prompt2resume: AI-Powered Resume Generator

## 🗂 Overview
`prompt2resume` is a web-based tool that generates tailored resumes from paragraph-style prompts using AI. It allows users to input raw resume content and produces structured, well-formatted resumes using predefined templates and AI-powered NLP.

---

## 📌 Core Features
- 📥 Input paragraph-style resume content
- 🧠 NLP processing (Python microservice)
- 🎨 Apply preloaded resume templates
- 📄 Generate PDF resumes
- 🕒 Journaling system to track prompt versions and generated resumes (like Git)
- 💾 Download or export final resumes

---

## 🧱 Tech Stack

| Layer          | Technology                |
|----------------|---------------------------|
| Frontend       | React / Next.js (TypeScript) |
| Backend        | Node.js / Express (TypeScript) |
| NLP Service    | Python (FastAPI + spaCy / Transformers) |
| Resume Engine  | HTML → PDF rendering |
| Versioning     | Journaling system with timestamped snapshots |
| Dev Tools      | Git, VSCode, ESLint, Prettier |

---


---

## 🔜 Upcoming Milestones

- [ ] Create and test NLP parser
- [ ] Set up frontend + backend skeleton
- [ ] Create first working pipeline: prompt → NLP → resume data
- [ ] Connect front and backend
- [ ] Add 1–2 resume templates
- [ ] Render and export PDF
- [ ] Polish UI & deploy

---

## 🧠 NLP Microservice Notes

- Tokenization + Named Entity Recognition (NER)
- Convert paragraphs into structured data (e.g. company, title, duration)
- Rewriting for clarity, tone, or brevity (optional)

---

## ✅ MVP Requirements

- [ ] Upload or enter text prompt
- [ ] Generate resume using a basic template
- [ ] Save journal entry of input + output
- [ ] View/download generated resume

---

## 🚀 Stretch Goals

- [ ] Template picker & preview
- [ ] Resume score (format & content)
- [ ] Collaborative editing
- [ ] Upload existing resume to extract content (OCR)

## 📐 Monorepo Structure
