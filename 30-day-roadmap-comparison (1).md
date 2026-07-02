# 30-Day Roadmap: Prompt A vs Prompt B

---

## PROMPT A — No Context (Generic Output)

**Topic chosen:** "Learn programming" (since no domain was specified, a generic AI would likely default to something broad like this — this is itself the first sign of the problem)

### Week 1 — Foundations
- **Milestone:** Understand basic programming concepts
- **Daily tasks:** 1 hr/day on syntax, variables, loops, conditionals (assumed pace)
- **Resources:** freeCodeCamp, Codecademy (generic suggestions)
- **Project:** Build a calculator

### Week 2 — Intermediate Concepts
- **Milestone:** Functions, data structures, basic OOP
- **Daily tasks:** Practice problems, small exercises
- **Resources:** W3Schools, YouTube tutorials
- **Project:** To-do list app

### Week 3 — Applied Practice
- **Milestone:** Work with APIs / files / a framework
- **Daily tasks:** Follow along with tutorials
- **Resources:** Official docs
- **Project:** Small CRUD app

### Week 4 — Consolidation
- **Milestone:** Build something end-to-end
- **Daily tasks:** Debugging, polishing
- **Resources:** Stack Overflow, GitHub
- **Project:** Capstone project (unspecified)

**Final outcome:** "You'll have a solid foundation in programming and be ready for the next step."

---

## PROMPT B — With Context (Personalized Output)

**Context supplied:**
- Current Situation: Student
- Current Skills: Python, basic web development
- Goal: Become an AI Engineer
- Available Time: 2 hrs/day
- Experience Level: Beginner-Intermediate
- Preferred Learning Style: Projects + Videos

### Week 1 — ML & Python Foundations for AI
**Milestone:** Comfortable with NumPy/Pandas and core ML concepts (supervised vs unsupervised, train/test split)

| Day | Task | Resource |
|---|---|---|
| 1–2 | NumPy/Pandas fundamentals (you already know Python, so skip basic syntax) | Kaggle "Pandas" micro-course (video+hands-on) |
| 3–4 | Core ML concepts: regression, classification | StatQuest YouTube playlist |
| 5–6 | Scikit-learn: train your first model | Scikit-learn "Getting Started" + follow-along notebook |
| 7 | **Project:** Predict house prices with linear regression (Kaggle housing dataset) | — |

### Week 2 — Neural Networks & Deep Learning Basics
**Milestone:** Build and train a simple neural net from scratch and with a framework

| Day | Task | Resource |
|---|---|---|
| 8–9 | Neural net theory: forward/backward pass | 3Blue1Brown "Neural Networks" series (video) |
| 10–11 | PyTorch basics (chosen since most LLM/RAG work uses it) | PyTorch 60-min blitz |
| 12–13 | Build an image classifier | PyTorch official MNIST tutorial |
| 14 | **Project:** MNIST digit classifier, get it above 95% accuracy | — |

### Week 3 — LLMs & Prompting (bridges into your existing Claude work)
**Milestone:** Understand how LLMs work and build your first LLM-powered app

| Day | Task | Resource |
|---|---|---|
| 15–16 | Transformer architecture basics | "Illustrated Transformer" (Jay Alammar, article) |
| 17–18 | Prompting techniques (you've already got hands-on depth here from ABTalks) | Anthropic's prompt engineering docs |
| 19–20 | Anthropic API: build a small script using it | docs.claude.com quickstart |
| 21 | **Project:** CLI tool that summarizes any PDF using the Claude API | — |

### Week 4 — RAG Fundamentals & Capstone
**Milestone:** Ship a working RAG mini-app

| Day | Task | Resource |
|---|---|---|
| 22–23 | Embeddings + vector databases (conceptual) | Pinecone "Learn" section (video+article) |
| 24–25 | Build a simple RAG pipeline | LangChain quickstart, or raw API + FAISS |
| 26–27 | Connect it to a small dataset (e.g., your nursery business docs, or your AI roadmap notes) | — |
| 28–29 | Polish, add a basic UI (Streamlit) | Streamlit docs |
| 30 | **Capstone Project:** A RAG-based Q&A tool over a document set of your choice, deployed and shareable | — |

**Final outcome:** By Day 30, you'll have built 4 portfolio projects (regression model, image classifier, Claude-API CLI tool, RAG app), have hands-on exposure to the exact stack (PyTorch, LLM APIs, RAG) your 12-month AI Engineer roadmap calls for in months 1–3, and have a working project you could post about on LinkedIn.

---

## Comparison

### 1. Which roadmap feels more personalized?
Prompt B, clearly. It skips things you already know (basic Python syntax), picks a framework (PyTorch) based on where you're headed (LLM/RAG work), and even ties the capstone project back to things already in your world (your nursery business data, your existing AI roadmap). Prompt A is a roadmap for "a generic learner" — it could apply to literally anyone learning to code, which means it's optimized for no one in particular.

### 2. Which one would you actually follow?
Prompt B. A generic plan gives you tasks; a context-aware plan gives you a *reason* for each task and paces it against your real constraint (2 hrs/day) instead of assuming unlimited time. Follow-through tends to break down when a learner can't see why a step applies to them — Prompt A has that failure mode built in.

### 3. What role did context play in improving the result?
Context did three things a good prompt alone can't:
- **Cut the fat** — skipped material you'd already covered (basic syntax) instead of wasting week 1 re-teaching Python.
- **Set the right destination** — "become an AI Engineer" produced an ML → DL → LLM → RAG progression instead of a generic "learn to code" arc.
- **Calibrated pace and format** — 2 hrs/day and a projects+videos preference shaped both the daily task size and the resource types picked, rather than defaulting to a one-size-fits-all cadence.

In short: the instruction ("create a roadmap") stayed the same in both prompts. What changed the output was entirely the *context* — this is a clean demonstration that specificity about the *user*, not just the *task*, is what turns an AI response from generic to genuinely useful.
