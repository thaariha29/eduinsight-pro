# EduInsight Pro 🎓

> AI-powered education platform that personalizes learning, bridges language gaps, and prevents student dropout.

**CodeFusion 2026 Grand Finale | Track 2: Education & Learning**

---

## 🚨 The Problem

Learning remains inaccessible, ineffective, and inequitable for millions of students:
- **Language barriers** block comprehension for non-English-speaking students
- **No personalization** — one curriculum for 40 students with 40 different needs
- **Dropout goes undetected** until it's too late for intervention
- **Teachers lack data** to identify which students need help, and how

---

## ✅ The Solution

EduInsight Pro is a 4-module AI-powered education platform addressing these gaps end-to-end:

| Module | What it does |
|--------|-------------|
| 🎓 AI Study Coach | Generates personalized learning paths for any topic + adaptive quizzes + AI tutor chat |
| 📊 Classroom Analyzer | Upload class data → AI creates per-student intervention plans with 4-week recovery roadmaps |
| 🌐 LearnLang | Translates & simplifies educational content into 8 regional Indian languages with adaptive practice |
| 🚨 Dropout Predictor | Real-time risk scoring with neural-pulse visualization + AI class health insights |

---

## 🛠️ Tech Stack

- **Frontend:** React (single-file, zero build step)
- **AI:** GROQ API (learning paths, intervention plans, translations, class insights)
- **Styling:** Pure CSS-in-JS with design tokens
- **Charts:** Custom SVG (scatter plot, progress bars, risk rings)
- **Data:** CSV upload support + demo dataset

---

## ⚡ Features

### AI Study Coach
- Enter any topic → AI generates a personalized 6-step learning path with time estimates and free resources
- Pre-built paths for ML, Data Structures, Python, Web Development
- 3-topic quiz bank with instant feedback and scoring
- Live AI tutor chat for any question

### Smart Classroom Analyzer
- Upload CSV/Excel with student data
- Click any student → AI generates: diagnosis, 3 immediate actions, 4-week recovery plan, parent SMS draft, language-specific support tip
- Sort by risk or name, filter at a glance
- Class-level stats: high-risk count, avg score, avg attendance

### LearnLang — Multilingual Support
- Supports: Tamil, Hindi, Telugu, Malayalam, Gujarati, Bengali, Kannada, Marathi
- 3 levels: Beginner, Intermediate, Advanced
- Output: native script translation + romanized pronunciation + simplified English + key terms + cultural context
- Adaptive practice sentence generator

### Dropout Risk Predictor
- Neural-pulse animated risk rings for each student (signature design element)
- Scatter plot: Attendance vs Score colored by risk tier
- Filter by High / Medium / On Track
- AI generates: Class Health Score, predicted dropouts, systemic risks, 4 teacher recommendations, urgent alert

---

## 🚀 Running Locally

```bash
# Clone the repo
git clone https://github.com/thaariha29/eduinsight-pro

# Install dependencies
npm install react react-dom

# Add your Anthropic API key to environment
export GROQ_API_KEY=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

# Run
npm start
```

Or open `EduInsightPro.jsx` directly in any React sandbox (CodeSandbox, StackBlitz).

---

## 📊 Scoring Alignment

| Criterion | How we address it |
|-----------|------------------|
| **Problem Understanding (20)** | Directly targets language barriers, lack of personalization, and dropout — all named in Track 2 challenge |
| **Technical Execution (35)** | Live AI features, real data viz, CSV upload, quiz engine, multilingual output |
| **Creativity & Innovation (10)** | Neural-pulse risk rings, AI-generated intervention plans, adaptive multilingual practice |
| **User Experience (10)** | Dark theme, instant feedback, clear navigation, accessible color coding |
| **Feasibility & Impact (15)** | Works on any device, deployable on Vercel/Netlify, real problem affecting millions of Indian students |
| **Documentation (10)** | This README + inline code comments |

---

## 👤 Team

**Thaariha** — Solo participant  
B.Tech AI & Data Science, Sri Shakthi Institute of Engineering and Technology, Coimbatore  

---

## 📄 License

MIT — built for CodeFusion 2026 Grand Finale
