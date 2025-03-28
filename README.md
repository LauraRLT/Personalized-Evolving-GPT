# 🧠 Personalized AI System for an Evolving Tutor That Self-Manages

This is a shareable framework for anyone who wants to turn ChatGPT into a **personalized, adaptive learning system** — one that not only teaches you *what* you want to learn, but also learns about *you* and how to support you best.

Designed to be modular, memory-aware, and customizable, this GPT assistant evolves with you through structured file inputs that guide its behavior, pacing, and tone. It’s especially helpful for neurodivergent learners, self-directed students, or anyone who needs a 24/7 tutor with executive-function backup.

---

## ✨ What Makes This Different

Most GPTs are one-off tools or static prompts. This is a **living, file-based assistant** that evolves with you — capable of tracking:

- Your learning goals and obstacles  
- Your focus and energy patterns  
- Your preferred tone and interaction style  
- Your reminders, insights, and unresolved questions

It does this by prompting you to edit existing versions of files loaded in the Knowledge (Configure) settings of custom GPT or to add new files. It can either automatically generate files and updates for you or help you to manually change and evaluate its system. Just delete the old version of the file, upload the new one, and update the GPT. All active chats will update to the latest active version with your next message.

⚠️ **Note:** Occasionally, GPT may fail to generate a file download. If that happens, just ask it to display the content in a copy-paste code block instead. You can then manually save it using any text editor (e.g., Notepad) — just make sure to save it as “All Files” with the appropriate `.md` extension.

---

## 🔧 What It Can Do

- Act as a **personalized tutor**, using Socratic prompts and tailored explanations  
- Adjust based on energy, sleep, and real-world context  
- Remind you when to take breaks or end sessions for the day
- Track learning struggles and help you revisit difficult concepts  
- Celebrate small wins and reinforce confidence  
- Adapt its behavior over time as your needs change

---

## 🧩 Core Components

All files are versioned and loaded into the GPT’s **Knowledge** section (Configure tab). These files govern behavior, context, pacing, and updates. Copy the contents of Text_for_Prompt_Box.md into the ‘Instructions’ field on the Configure page of the GPT's settings.

- `instructions_initial.md` — defines GPT behavior, interaction style, and file protocols  
- `learning_tracker_initial.md` — tracks concepts practiced, mistakes made, and strategies to revisit  
- `reminders_initial.md` — lists active tasks, habits, and prompts long-term nudges  
- `daily_log_as_of_initial.md` — tracks energy, sleep, routines, and focus notes  
- `solution_archive_initial.md` — stores reusable outputs, helpful GPT responses, or creative samples  
- `index_initial.md` — describes how all files connect  
- `health_baseline_initial.md` *(optional)* — stores personal and cognitive context  
- GPT will also help you create and customize files based on your personal goals and workflow

---

## 🧠 Who This Is For

- Independent learners  
- Neurodivergent students  
- Coders, researchers, writers, and builders  
- Anyone who wants GPT to scaffold *how* they learn, not just *what* they learn

---

## 🪄 How to Use It

1. Create your own [Custom GPT](https://chat.openai.com/gpts) *(paid plan required)*
2. Upload the `*_initial.md` files to the GPT’s **Knowledge** section under Configure
3. Copy the contents of Text_for_Prompt_Box.md into the “Instructions” field under Configure
4. Name your GPT something meaningful, like `Learning Ally` or `Meta-Tutor`
5. Start your first session with:

```
Manual File Sync: Load index_initial.md.  
Manual File Sync: Load all files listed in index_initial.md.  
Help me update and adjust this system based on my goals and needs.  
I: (insert brief description here)
```

6. As you use the system, it will prompt you when to update files based on insights, routines, or patterns

---

## 💬 Sample Prompts

- “Let’s review what I struggled with last week.”  
- “Why is this solution wrong? Help me fix it without giving the answer.”  
- “Add this insight to my learning tracker.”  
- “What do you suggest I practice next?”  
- “Can you show me what we worked on last session?”

---

## 🔁 Designed to Evolve

This system isn’t rigid — it’s a scaffold for your growth. You can:

- Change the language and tone  
- Add new files (e.g. `writing_archive.md`, `vocab_tracker.md`) and update `index.md` accordingly  
- Fork the setup for writing, research, creative projects, or fitness coaching

---

### 🙌 Final Thought

This isn’t just a chatbot — it’s a self-aware, memory-powered support system.  
It scaffolds your learning. It adapts to your needs. And it keeps track when you can’t.

> Use it. Fork it. Share it. You deserve to learn your way.

---
**Version:** v2.0  
**Last updated:** 2025-03-28
