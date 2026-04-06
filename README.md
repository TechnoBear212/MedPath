# 🩺 MedPath

**MedPath** is an AI-powered clinical learning platform designed to help medical students and trainees sharpen their diagnostic reasoning through interactive cases, Socratic questioning, and spaced repetition.

---

## 🚀 Features

### 🏠 Home Dashboard
- Tracks:
  - Cases completed
  - Average score
  - Daily streak
- Automatically identifies **weak areas by system**
- Helps you focus your study efficiently

---

### 🧠 AI Case Generation
- Fully generated patient cases including:
  - Chief complaint
  - Vitals
  - History of Present Illness (HPI)
  - Physical exam findings
  - Investigations
- Filter by system:
  - Cardiology, Neurology, Renal, etc.
- Or generate **random cases** for mixed practice

---

### 🎓 Socratic AI Tutor
- Does NOT give direct answers
- Guides your reasoning with questions like:
  - *“What finding supports that diagnosis?”*
  - *“Why would you rule out X?”*
- Mimics real clinical teaching
- Works in both:
  - AI-generated cases
  - Offline case mode

---

### 📊 End Session Feedback
- After each case:
  - Score (0–100)
  - Strengths identified
  - Knowledge gaps highlighted
  - 2–3 high-yield clinical pearls
  - Final diagnosis revealed

---

### 📈 Progress Tracking
- Tracks performance across sessions
- Identifies weak topics over time
- Feeds insights back into dashboard

---

### 📚 Clinical Cases
Two modes available:

#### 1. AI-Generated Cases
- Unlimited unique cases
- Covers all systems

#### 2. Offline Case Bank
- 8 pre-written real cases:
  - Cardiology
  - Respiratory
  - Renal
  - Gastroenterology
  - Neurology
  - Endocrine
  - Haematology
  - Musculoskeletal
- Works **without internet**

---

### ❓ Quiz Bank
- Categories:
  - Anatomy
  - Pharmacology
  - Physiology
  - Biochemistry
  - Pathology
  - Clinical Reasoning
- Choose:
  - 5 or 10 questions
- Features:
  - Instant feedback (✅ correct / ❌ incorrect)
  - Explanation for:
    - Correct answer
    - Incorrect options
  - End-of-quiz performance summary

---

### 🔁 Spaced Repetition Engine (SRS)
Powered by a simplified **SM-2 algorithm** (like Anki)

#### How it works:
- **Score ≥ 80%**
  - Interval increases
  - Topic shown less frequently
- **Score 60–79%**
  - Interval stays similar
  - Slight decrease in ease
- **Score < 60%**
  - Interval resets to 1 day
  - Ease decreases significantly

#### Features:
- Due-count badge on home screen
- Dedicated SRS screen showing:
  - Next review date
  - Interval
  - Last score
- One-tap review → directly launches relevant case/quiz

---

### 📊 Advanced Progress Insights
- Topic-wise progress bars:
  - 🟢 Green (Strong)
  - 🟡 Amber (Needs work)
  - 🔴 Red (Weak)
- Rolling average across sessions
- Streak tracking for consistency

---

## 📱 Offline Support
- Offline case bank available
- Continue learning anywhere
- Socratic tutor still functional in offline mode

---

(Goal)
MedPath is built to:
- Improve clinical reasoning
- Reinforce learning through active recall
- Simulate real-world clinical thinking
- Make studying smarter, not harder

---

## ⚙️ Tech Stack (Optional — edit as needed)
- Frontend: HTML / CSS / JavaScript
- Backend: (Add if applicable)
- AI Integration: (Add model/service used)
- Storage: LocalStorage / Database (if applicable)

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/medpath.git
cd medpath
