# 1-Year AI Safety Alignment Research Roadmap 🛡️🤖

Welcome to my self-directed, 1-year technical roadmap to transition from absolute scratch to building AI alignment and safety research projects. This repository tracks my progress, notes, and code implementations as a Class 9/10 student dedicating **15 hours per week**.

---

## 📊 Weekly Time Allocation (15 Hours)
*   **Mon–Fri (5 hrs):** 1 hour/day of core programming, debugging, and open-source contributions.
*   **Saturday (5 hrs):** Deep theory, academic papers, and math intuition.
*   **Sunday (5 hrs):** Practical engineering, building models, and alignment labs.

---

## 🗺️ The 4-Phase Roadmap

### 🧱 Phase 1: The Coding & Math Bedrock (Months 1–3)
**Focus:** Absolute mastery of Python syntax, version control, and core mathematical intuition.

- [ ] **Programming Fundamentals**
  - [ ] Complete Harvard's *CS50P: Introduction to Programming with Python*.
  - [ ] Build 3 complex text-based games from scratch (logic and OOP practice).
  - [ ] Master Git/GitHub workflows (branching, committing, PRs).
- [ ] **Data Science & Math Basics**
  - [ ] Complete Kaggle Learn courses: *Python*, *Pandas*, and *Data Visualization*.
  - [ ] Watch 3Blue1Brown's *Essence of Linear Algebra* and *Essence of Calculus*.
  - [ ] Core focus: Matrices, vectors, dot products, derivatives, and gradients.

### 🤖 Phase 2: Deep Learning & Transformers (Months 4–6)
**Focus:** Transitioning from static code to building architectures that learn from data.

- [ ] **Deep Learning Foundations**
  - [ ] Watch 3Blue1Brown's *Neural Networks* series.
  - [ ] Complete Fast.ai's *Practical Deep Learning for Coders* (Part 1).
  - [ ] Implement a multi-layer perceptron (MLP) from scratch using only NumPy.
- [ ] **The Transformer Architecture**
  - [ ] Master PyTorch basics (Tensors, Autograd, Optimization loops).
  - [ ] Code along with Andrej Karpathy's *Neural Networks: Zero to Hero* playlist.
  - [ ] **Milestone:** Replicate a mini-GPT (GPT-2 scale) from scratch in Google Colab.

### 🛡️ Phase 3: AI Safety Specialization (Months 7–9)
**Focus:** Diving into technical alignment paradigms and specialized safety frameworks.

- [ ] **Theory & Alignment Curriculums**
  - [ ] Work through the *BlueDot Impact: AI Safety Fundamentals (Alignment Course)* modules.
  - [ ] Study concepts: Deceptive alignment, reward hacking, sharp left turns, and RLHF.
- [ ] **Technical Tracks (Pick One or Both)**
  - [ ] *Mechanistic Interpretability:* Complete the introductory coding blocks on `arena.education` for Mech Interp. Learn to use the **TransformerLens** library.
  - [ ] *Model Evaluation (Evals):* Learn the **Inspect AI** framework (by the UK AI Safety Institute) to write automated vulnerability testing pipelines.

### 🛠️ Phase 4: Capstone Alignment Projects (Months 10–12)
**Focus:** Building, documenting, and publishing open-source alignment projects.

- [ ] **Project 1: The Automated Jailbreak Evaluator (Evals)**
  - [ ] Create a pipeline that feeds adversarial prompts to an open-source LLM and scores its safety boundaries.
- [ ] **Project 2: The Neuron Activation Explorer (Interpretability)**
  - [ ] Use TransformerLens to isolate and graph specific induction heads or concept neurons in a small language model.
- [ ] **Community & Portfolios**
  - [ ] Document all code with high-quality `README.md` files in this repository.
  - [ ] Host model demos or evaluation sets on Hugging Face.
  - [ ] Write a summary post of findings on the AI Safety Alignment Forum or LessWrong.

---

## 🛠️ Repository Structure
Keep notes, exercises, and projects clean:
```text
├── phase-1-bedrock/
│   ├── math-notes.md
│   └── python-exercises/
├── phase-2-deep-learning/
│   ├── gpt-from-scratch/
│   └── pytorch-labs/
├── phase-3-safety-labs/
│   ├── mech-interp-notebooks/
│   └── eval-scripts/
└── phase-4-capstone-projects/
    ├── README.md (Project summaries)
    └── project-code/
```

---

## 📌 Rules I Live By
1. **The 30/70 Rule:** 30% of the time reading/watching tutorials; 70% of the time actually writing and breaking code.
2. **School Comes First:** During school board/midterm exam weeks, AI safety hours drop to 0. Consistency over long periods beats weekend cramping.
3. **Reproducibility:** Every script I write must be runnable by someone else using a free Google Colab notebook.
