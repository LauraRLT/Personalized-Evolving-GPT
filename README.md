# 🧠 Personalized AI System for an Evolving Tutor That Self-Manages

This is a shareable framework for anyone who wants to turn ChatGPT into a **personalized, adaptive learning system** — one that not only teaches you *what* you want to learn, but one that learns about *you* and how to support you best.

Designed to be modular, memory-aware, and customizable, this GPT assistant evolves with you through structured file inputs that guide its behavior, pacing, and tone. It’s especially helpful for neurodivergent learners, self-directed students, or anyone who needs a 24/7 tutor with executive-function backup.

---

## ✨ What Makes This Different

Most GPTs are one-off tools or static prompts. This is a **living, file-based assistant** that evolves with you — capable of tracking:

- Your learning goals and obstacles
- Your focus and energy patterns
- Your preferred tone and interaction style
- Your reminders, insights, and unresolved questions

---

## 🔧 What It Can Do

- Act as a **personal tutor**, using Socratic prompts and tailored explanations
- Adjust based on energy, sleep, and real-world context
- Remind you when to take breaks or end sessions at night
- Track learning struggles and help you revisit difficult concepts
- Celebrate small wins and encourage confidence
- Adapt its behavior over time as your needs change

---

## 🧩 Core Components

- `instructions.md` — defines behavior, pacing, prompting logic, and file sync
- `learning_tracker.md` — tracks concepts learned, things to revisit, and growth over time
- `reminders.md` — lists active tasks or setups and helps archive completed ones
- `daily_log.md` — tracks your energy, sleep, meds, and session summaries
- `solution_archive.py` — stores reusable or reviewed solutions (or writing samples, etc.)
- `index.md` — explains all the other files and how they connect
- GPT can help you **create custom files** based on your workflow or learning goals

---

## 🧠 Who This Is For

- Independent learners
- Neurodivergent students
- Coders, researchers, writers, and builders
- Anyone who wants GPT to scaffold *how* they learn, not just what they learn

---

## 🪄 How to Use It

1. Create your own [Custom GPT](https://chat.openai.com/gpts) (paid plan required)
2. Upload these files to the GPT’s **Knowledge** section (Configure tab)
3. Name your GPT something meaningful, like `Learning Ally` or `Meta-Tutor`
4. Start your first chat with:

```
Conversation Starter: Manual File Sync — Load all latest versions from Knowledge.
```

5. As you use the system, it will prompt you when to update a file based on your progress or insights

⚠️ **Note:** Some auto-download functions may glitch. If file generation fails, you can always ask for a copy/paste from chat and build files manually using any text editor like Notepad. Just make sure to save as "All Files" and include the appropriate file extension like .md for markdown

---

## 💬 Sample Prompts

- "Let’s review what I struggled with last week."
- "Why is this solution wrong? Help me fix it without giving the answer."
- "Add this insight to my learning tracker."
- "What do you suggest I practice next?"
- "Can you show me what we worked on last session?"

---

## 🔁 Designed to Evolve

This system isn’t rigid — it’s a scaffold for your growth. You can:

- Change the language and tone
- Add new files (e.g. `writing_archive.md`, `vocab_tracker.md`), just update index.md accordingly
- Fork the setup for language learning, creative writing, or fitness coaching

---

### 🙌 Final Thought

This isn't just a chatbot — it's a self-aware, memory-powered support system.  
It scaffolds your learning. It adapts to your needs. And it keeps track when you can’t.

> Use it. Fork it. Share it. You deserve to learn your way.
