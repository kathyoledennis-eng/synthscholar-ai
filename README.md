# SynthScholar Academy

An open-source blueprint for a **fully autonomous AI-run online university / skill platform**.

No humans needed for daily operations. AI agents create courses, teach students, grade work, handle sign-ups, and improve themselves.

## Vision
- Teach hot 2026 skills: Generative AI, Prompt Engineering, Agentic Workflows, Data Analysis with AI.
- Hyper-personalized learning with 24/7 AI tutors.
- Freemium model: Free intro modules, cheap subscriptions.
- Verifiable certificates on blockchain (future).
- 100% open-source and free to run locally.

## Core Idea (How It Works)
Multi-agent system using free/open tools:
- **LangGraph** for smart workflow control (loops, decisions, fixes errors).
- **CrewAI-style roles** for agents like:
  - Planner Agent: Finds trending skills and plans new courses.
  - Content Agent: Writes lessons, quizzes, projects.
  - Tutor Agent: Chats with each student, adapts lessons.
  - Grader Agent: Marks work automatically.
  - Growth Agent: Markets on social media.
  - Optimizer Agent: Makes everything better from feedback.

## Flagship Course Example: Generative AI Mastery
1. What is GenAI in 2026?
2. Prompt basics (zero-shot, few-shot).
3. Advanced techniques (chain-of-thought, role-playing).
4. Multimodal prompting (text + images/video).
5. Intro to agents & workflows.
... (more modules can be added)

## How to Run This Locally (Free, No API Costs)
1. Install Python (free from python.org).
2. Install Ollama (free local AI runner): https://ollama.com
   - Run Ollama and download a free model: `ollama run llama3` (or better ones like deepseek-coder).
3. Install libraries: `pip install langgraph crewai`
4. Write simple scripts using Ollama as the brain (no paid APIs needed).
5. Run a demo agent team!

## Next Steps
- Fork this repo and add your own courses.
- Help build real agents!
- Share on X/Reddit: #AI #OpenSource #LearnAI

License: MIT (free to use/copy/change)
