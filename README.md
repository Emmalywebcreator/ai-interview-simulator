# 🎓 AI Teaching Interview Simulator

A voice/text-based AI simulation tool that mimics real teaching interviews and evaluates candidates on **clarity, structure, communication, and teaching ability**.

This project is designed as a **flight simulator for teaching interviews** — allowing users to practice real-world tutoring and classroom explanations in a safe, repeatable environment.


## 🚀 What this project does

This system simulates a realistic teaching interview where an AI:

* Asks structured interview questions (starting with “Introduce yourself”)
* Accepts user answers (text or voice)
* Evaluates responses based on teaching performance
* Scores clarity, structure, and engagement
* Provides feedback
* Asks follow-up questions dynamically


## 🧠 Core Idea

Most interview prep tools test *knowledge*.

This system tests:

* Communication under pressure
* Teaching clarity
* Real classroom thinking
* Ability to simplify concepts
* Handling student-like interruptions

Think of it as:

> 🎮 A flight simulator — but for teaching interviews


## 🧩 Features (MVP)

* 🗣️ AI-powered interview questions
* ✍️ Text-based answer input (voice-ready architecture)
* 📊 AI evaluation system (0–10 scoring)
* 💬 Structured feedback (strengths + improvements)
* 🔁 Dynamic follow-up questions
* 🎯 Teaching-focused prompts (not generic interviews)
* 📁 Session history tracking


## 🏗️ Project Structure

```
ai-interview-simulator/
│
├── app.py                  # Streamlit UI entry point
├── interview_engine.py    # Core AI logic (questions + evaluation)
├── prompts.py             # System prompts and interview behavior rules
├── speech_to_text.py      # (Optional) Voice input module
├── requirements.txt
│
└── utils/
    ├── scorer.py          # Scoring utilities
    └── session_state.py   # Session tracking helpers
```


## ⚙️ How It Works

### 🔄 Interview Flow

```
Start Session
   ↓
AI asks question (e.g. Introduce yourself)
   ↓
User responds
   ↓
AI evaluates:
   - clarity
   - structure
   - teaching quality
   ↓
AI returns:
   - score (0–10)
   - feedback
   ↓
AI generates follow-up question
   ↓
Repeat
```


## 🧪 Interview Stages

The simulator follows a structured progression:

### Stage 1: Introduction

* “Introduce yourself as a tutor”
* Communication clarity test

### Stage 2: Teaching Ability

* Explain concepts to children
* Use examples and analogies

### Stage 3: Classroom Scenarios

* Handling distracted students
* Managing confusion

### Stage 4: Pressure Test

* Time-limited explanations
* Unexpected follow-ups


## 🧠 Evaluation Criteria

Each response is evaluated on:

### Communication

* Clarity
* Structure
* Flow
* Avoidance of rambling

### Teaching Quality

* Simplicity of explanation
* Use of examples
* Age-appropriate language

### Engagement

* Ability to maintain attention
* Questioning techniques
* Interaction style


## 🛠️ Tech Stack

* Python 3.10+
* Streamlit (UI)
* Google Gemini API (LLM engine)
* SpeechRecognition (optional voice input)


## 📦 Installation

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/ai-interview-simulator.git
cd ai-interview-simulator
```


### 2. Install dependencies

```bash
pip install -r requirements.txt
```


### 3. Add API key

Create a `.env` file or set directly:

```bash
export GEMINI_API_KEY="your-api-key"
```

---

### 4. Run the app

```bash
streamlit run app.py
```


## 💡 Example Session

### AI:

> Please introduce yourself as a tutor applying for a teaching position.

### User:

> I am a teacher with 2 years experience helping children understand math...

### AI Evaluation:

**Score: 7/10**

**Strengths:**

* Clear introduction
* Relevant experience mentioned

**Improvements:**

* Add specific examples
* Improve structure (start → experience → impact)

### Follow-up:

> Can you explain how you would teach addition to a 7-year-old child?


## 🎯 Why this project is different

Unlike traditional interview prep tools, this system:

* Simulates real teaching pressure
* Evaluates communication, not just correctness
* Mimics student interactions
* Adapts in real-time
* Focuses on *teaching performance*, not job trivia


## 🔮 Future Improvements

### Phase 2

* Voice-based interviews
* JSON-based scoring system
* Real-time interruption simulation

### Phase 3

* “Distracted student mode”
* Classroom behavior simulation
* Multi-student scenarios

### Phase 4

* Full tutor certification training system
* Analytics dashboard
* Progress tracking over time


## ⚠️ Limitations (MVP)

* No persistent database yet
* Basic scoring parser (text-based)
* No authentication system
* Voice feature optional


## 🤝 Contribution

This project is designed for rapid iteration.

Feel free to:

* Improve prompts
* Add new interview stages
* Enhance scoring logic
* Build UI improvements


## 📌 Vision

> To build the most realistic AI simulation system for training communication-heavy roles like teaching, tutoring, and customer interaction.


## 🧑‍💻 Author

Built as an experimental AI training simulator for improving real-world teaching communication skills.
