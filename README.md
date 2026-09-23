# 🎓 EduSphere AI — AI-Powered Education Platform

> **Hackathon Submission — Track 4: Education**  
> *A unified, intelligent learning and teaching ecosystem that enhances personalized learning, simplifies teaching, and improves student outcomes.*

---

## 🌟 Overview

EduSphere AI bridges the gap between students seeking mastery and educators striving for personalized pedagogy. Designed specifically for **Track 4: Education**, it integrates all 7 foundational pillars into a cohesive, high-performance web platform:

```
React Frontend
│   ├── 🔐 Login/Register
│   ├── 💡 AI Doubt Solver
│   ├── 📝 Quiz Generator
│   ├── 📋 Assignment Generator
│   ├── 📅 Study Planner
│   ├── 🎯 Career Guidance
│   └── 📊 Progress Dashboard
```

---

## 🚀 Key Modules & Capabilities

### 1. 🔐 Dual-Persona Login & Register
- **Student & Educator Roles**: Instantly toggle between Student mode (learning & drills) and Teacher mode (curriculum design & cohort insights).
- **1-Click Reviewer Demo**: Pre-configured demo logins for both Student and Teacher roles for fast hackathon judging.
- **Persistent State**: Stores user XP, study streaks, solved doubts, and quiz histories in `localStorage`.

### 2. 💡 AI Doubt Solver
- **Step-by-Step Deductive Breakdown**: Deconstructs questions into numbered sub-steps with conceptual rationale.
- **LaTeX & Code Formatting**: Displays clean mathematical derivations and syntax-highlighted code.
- **Intuitive Mental Models**: Provides real-world analogies explaining *why* a principle works.
- **Understanding Micro-Drill**: Generates a follow-up challenge question with revealable hints to confirm mastery.

### 3. 📝 Adaptive Quiz Generator & Arena
- **Dynamic Assessment Creation**: Configure subject, difficulty (Beginner, Medium, Advanced), and question count.
- **Live Quiz Taking Arena**: Features an active countdown timer, question pagination, and instantaneous feedback.
- **Gamified Celebration**: Fires vibrant celebratory confetti upon scoring 70%+, rewarding XP points.
- **In-Depth Explanations**: Details why the correct answer is valid and breaks down distractor pitfalls.

### 4. 📋 Assignment & Rubric Generator
- **Bloom's Taxonomy Architecture**: Generates multi-part homework spanning foundational recall, practical implementation, and critical analysis.
- **Standardized Rubrics**: Outputs weighted assessment criteria (Exemplary, Proficient, Needs Improvement).
- **1-Click Export**: Copy clean Markdown or print formatted paper-ready student worksheets.

### 5. 📅 Dynamic Study Planner
- **Intelligent Backwards Planning**: Calculates optimal hours based on target exam dates and daily commitments.
- **Multi-Phase Schedules**: Automatically segregates preparation into Foundation Mastery and Timed Mock Simulation.
- **Interactive Checklists**: Real-time progress bar that updates dynamically as students complete daily milestones (+15 XP per task).

### 6. 🎯 Career Guidance & Skill Pathfinder
- **Dream Role Alignment**: Evaluates target careers (e.g. AI Engineer, Full Stack Cloud Architect, Data Scientist).
- **Skill Gap Matrix**: Highlights missing high-priority competencies with specific courses and tutorials to acquire them.
- **3-Stage Milestone Blueprint**: Outlines exact portfolio projects and recognized industry certifications.

### 7. 📊 Progress & Cohort Dashboard
- **Student View**: Visual subject mastery progress bars, weekly study hour histograms, streak counters (🔥), and unlocked badges.
- **Teacher View**: Cohort metrics (48 enrolled, 76.4% average comprehension, assignment turn-in rates, and flagged struggling topics).

---

## 🛠️ Tech Stack

- **Frontend**: React 18 + Vite
- **Styling**: Tailwind CSS with custom glassmorphism and modern gradients
- **Icons**: Lucide React
- **Celebration & UX**: Canvas Confetti
- **AI Engine**: Dual-mode engine supporting direct Google Gemini 1.5 Flash API calls with resilient built-in pedagogical fallbacks (100% offline and zero-setup reliable).

---

## ⚡ Getting Started & Running the Project

### Prerequisites
- Node.js (v18+)
- npm (v9+)

### Installation

1. Navigate to the project directory:
   ```bash
   cd C:\Users\hp\.gemini\antigravity\scratch\edusphere-ai
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Launch the development server:
   ```bash
   npm run dev
   ```

4. Open your browser at:
   ```
   http://localhost:3000
   ```

---

## 🔑 Optional: Live Gemini API Activation
EduSphere AI works completely out of the box with its built-in pedagogical engine. To activate live Google Gemini 1.5 Flash responses:
1. Click the **"Gemini Key"** button in the top navbar.
2. Enter your free Google Gemini API key.
3. Click **"Save & Activate"** — the indicator will turn green and live Gemini intelligence is instantly engaged.
