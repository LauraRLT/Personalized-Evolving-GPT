# 📓 CHANGELOG

## Version 2.0 – March 28, 2025

This release is a major overhaul of the personalized GPT system, built for long-term support, modularity, and adaptability across learning goals and support needs. New layouts were applied to many of the files and templates were added where necessary. Many files now include prompts to guide both the user and GPT through initial setup and customization.
Designed to make the system more flexible, scalable by GPT, and accessible to new users.

---

## 🛠️ Core Changes

- **Time handling clarified**: Filenames use UTC timestamps, while all content within files should follow the user's local timezone if provided
- **Tone generalized** to support users in any domain, not just coding or neurodivergent contexts
- **Improved structure and formatting** in all files for GPT readability and future customization

---

## 📂 File-by-File Changes

### `README.md`
- Rewritten and expanded based on changes to files
- Clearer setup instructions for Custom GPT creation
- Sample starting prompts adjusted
- New onboarding section with “How to Use It” and version tracking

---

### `instructions_*.md`
- Fully restructured and modularized into clearly labeled sections
- Refined tone for GPT-wide behavior, pacing, transparency, and energy awareness
- Prompts to guide user and GPT through initial setup were added
- New logic for file sync, version tracking, and memory protocols that should minimize bugs. 
- Logic for detailed file creation and download where split and moved to gpt_prompts_*.md to make it easier to adjust in future.
- Interaction style made more adaptable and coaching-focused
- GPT behavior rules expanded with “Minimal Answer Mode” and file update prompts

---

### `gpt_prompts_*.md` *(new file in v2)*
- Introduces structured commands and protocols for syncing, updating, or auditing files
- Includes new “File Update” and “File Write and Download” instructions as separate commands to help provide work arounds for issues with file downloads and prevent loss of information
- Supports manual workflows (copy/paste) and GPT-guided file editing
- Added “Strict Mode” to allow user to toggle GPT into a minimal response format to avoid GPT giving away answers or solutions

---

### `index_*.md`
- Fully rewritten to match new file structure and behaviors
- Now includes clear descriptions for each file and section
- Highlights which files are optional
- Adds notes for GPT to prompt user when a file is missing or should be created

---

### `daily_log_as_of_*.md`
- Now designed as a structured template
- Includes a detailed comment block for how to format entries and summaries
- Weekly summary logic added
- Time-of-day and symptom tracking expanded
- Added an example entry for reference

---

### `learning_tracker_*.md`
- Template-based format replaces open-ended structure
- Clear sectioning: Current topics, recent wins, chronological log
- Domain-neutral phrasing now works for any subject or skill area
- Added an example entry for reference

---

### `reminders_*.md`
- Moved from a checkbox list with tags to a more structured markdown layout
- Adds prompts for GPT to suggest archiving or deletion
- GPT reminders now include optional priority indicators
- Added example entries for reference and to encourage proper first setup

---

### `solution_archive_*.md`
- Rewritten to support reusable outputs in any domain
- Commented template structure added for consistency
- Supports code, creative writing, logic patterns, and walkthroughs
- Added an example entry for reference

---

### `health_baseline_*.md` *(new file in v2)*
- Provides a template for storing medical, mental health, sleep, and energy patterns
- Structured as a collaborative intake between GPT and user
- Optional and flexible — designed to support neurodivergence, executive function, or pacing needs

---

### `Text_for_Prompt_Box.md`
- Updated to match v2 file structure and timestamp behavior
- Clearer instructions for file loading, syncing, and scope across sessions
- GPT onboarding instructions rewritten for clarity

---

## ✅ Summary

Version 2 is more modular, GPT-readable, and adaptable across skill domains, learning styles, and support needs.  
It is ready to be forked, remixed, or expanded by users building custom GPTs for long-term coaching, habit tracking, or problem-solving.

---

📦 Released: 2025-03-28  
🏷️ Version: v2.0  
🛠️ Author: LauraRLT  
🤖 Powered in part by OpenAI's GPT-4o
