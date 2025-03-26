# index.md

This file serves as a master reference for all files in the system.  
It describes the purpose, contents, and relationships between each component.

---

## 📂 Core Files

### `README.md`
- Introductory overview for public use
- Explains the purpose, capabilities, and audience of the system

### `instructions.md`
- Defines the GPT’s behavior and logic
- Covers pacing, scaffolding style, memory, and file interaction rules

### `learning_tracker.md`
- Logs what the user has learned, what’s still hard, and what to revisit
- Used by GPT to suggest review topics and track growth

### `reminders.md`
- Stores active tasks, setup goals, and system TODOs
- GPT may display active reminders and suggest when to archive completed ones

### `daily_log.md`
- Tracks sleep, focus, energy, and session notes
- GPT uses this to adjust tone, pacing, and expectations in real time

### `solution_archive.md`
- Placeholder archive for past solutions, outputs, or reflections
- Can be used for reuse, retrospectives, or creative samples

---

## 🧠 Optional / Custom Files

These are user-specific or system extensions. GPT may help you create them.

### `writing_archive.md`
- For writing samples, drafts, or narrative reflections

### `vocab_tracker.md`
- For language learners or exam prep

### `custom_checklists.md`
- For tracking recurring task structures (e.g., project setup, review templates)

---

## 🧩 How Files Interact

- `instructions.md` governs **how** GPT behaves
- All other files give GPT **context** about you, your goals, and your recent progress
- GPT syncs files manually or automatically depending on your setup
- All files should follow consistent timestamp naming when versioning

---

## 🛠️ File Versioning Format

- Use the following convention for dated versions of core files:

```
[filename]_[MM-DD-YYYY-HHMM].md
```

Examples:
```
instructions_03-25-2025-2359.md
daily_log_as_of_03-26-2025-0030.md
```

- Use 24-hour **UTC time** and **US-format dates** for consistency

---

## ✅ Final Note

You can fork, extend, or simplify this system depending on your needs.  
The modular file structure allows for deep customization with minimal overhead.

Feel free to rename files, split logs, or add tracking tools that fit your workflow.
