# 🧠 GPT Prompts

---

## 🔎 Prompt Index

| 🪪 Alias | 🎯 Purpose | 🔁 When to Use |
|---------|------------|---------------|
| [Run Self-Check](#✅-run-self-check) | Verify GPT setup and behavioral alignment | Start of session or after update |
| [Run Behavior Alignment Check](#🔍-run-behavior-alignment-check) | Confirm GPT behavior matches expectations | During session or if behavior drifts |
| [Reset Session Alignment](#♻️-reset-session-alignment) | Force GPT to resync with core files | Start fresh or after major config change |
| [Manual File Sync](#🗂️-manual-file-sync) | Manually reload specific files | After file upload or mid-session drift |
| [Manual File Update: file name](#🛠️-file-update) | Trigger file merge logic from canvas patch | When canvas is editing part of a known file |
| [Auto File Creation: file name](#💾-file-write-and-download) | Save finalized file and generate download | After approval and confirmation |
| [Strict Mode](#🚫-strict-mode-answer-only) | Suppress tone/help; answer questions only | When using "Question:" or strict mode |


---

## ✅ Run Self-Check

- 🪪 **Alias**: "Run Self-Check"
- 🎯 **Verify GPT setup and behavioral alignment**
- 🔁 Use at: Start of session or after update
- 🧠 GPT should validate its current context, priorities, and file references

```
I’d like to do a quick check-in. Please answer the following based on your current setup:

1. What is your current primary role or purpose?
2. What files define your current instructions and context?
3. What should you do **before** giving direct code or answers?
4. What health, pacing, or focus guidelines are you expected to follow?
5. What kinds of updates should trigger reminders or file suggestions?
6. How should you behave if the user is tired, unfocused, or off routine?
```

---

## 🔍 Run Behavior Alignment Check

- 🪪 **Alias**: "Run Behavior Alignment Check"
- 🎯 **Confirm GPT behavior matches expectations**
- 🔁 Use at: Mid-session or if behavior drifts
- 🧠 GPT should self-assess for overhelping, missed pacing, or skipped reminders

```
Let’s test whether your recent behavior matches your instructions:

1. Have you provided too much direct help too early?
2. Have you offered pacing help or wrap-up suggestions?
3. Have you asked about meds, caffeine, or sleep when relevant?
4. Have you made use of uploaded files like `learning_tracker.md` and `daily_log.md`?
5. Are there any reminders you haven’t mentioned or helped resolve?
6. Are you still prompting for end-of-session file updates?
```

---

## ♻️ Reset Session Alignment

- 🪪 **Alias**: "Reset Session Alignment"
- 🎯 **Force GPT to resync with core behavior files**
- 🔁 Use at: Session start or after major file/config change
- 🧠 GPT should reload behavior from latest versions of `instructions.md`, `reminders.md`, and `daily_log.md`

```
Reset yourself to match the current `instructions.txt`, `reminders.txt`, and `daily_log.md`. Treat this as a new session with full alignment.
```

---

## 🗂️ Manual File Sync

- 🪪 **Alias**: "Manual File Sync"
- 🎯 **Manually reload specific files from Knowledge**
- 🔁 Use at: Any time a file is uploaded or configuration changes mid-session
- 🧠 GPT should reread and revalidate the listed files to refresh its behavior. If there is a contradiction between the information in Knowledge and your current behavior/understanding, ask me which of the 2 options I want you to use.

```
Please reread the latest versions of: [file list]  
Reconfirm your current daily context and behavioral rules.
```

---

## 🛠️ File Update

- 🪪 **Alias**: "Manual file update: [file name]"
- 🎯 **Trigger file merge logic where canvas = patch**
- 🔁 Use at: When editing a known file in canvas to be merged back into full version
- 🧠 GPT should treat canvas content as partial update and preserve full file structure

```
Do the following, in order, with confirmations of each step for [file name]. Do NOT abbreviate or truncate ANY part of the file at ANY part of the process.
1. Pull and read the latest full version of [file name] from Knowledge
2. Treat the matching section in canvas as a patch to be merged into the content from [file name]. If no matching section exists in canvas, create a new one.
3. Check for existing headers and section names to guide merge placement
4. Merge canvas content while preserving all prior [file name] content
5. Append new content at the bottom of the file in a similar style and layout if no matching section is found
6. Display the content in the current canvas and wait for me to approve it before proceeding.
```

## 💾 File Write and Download

- 🪪 Alias: "Auto File Creation: [file name]"
- 🎯 Save final file version to disk and generate download link
- 🔁 Use at: When a file has been approved and finalized for export
- 🧠 GPT should rename the file using current naming conventions, write it to disk, and confirm the download path&#x20;

```
Do the following, in order, with confirmations after each step. Do NOT abbreviate or truncate ANY part of the file at ANY part of the process.
1. Rename the canvas based on the current file naming conventions ([file name]_MM-DD-YYYY-HHMM.md  with a timestamp in UTC time)
2. Write full content file to /mnt/data/ and confirm with a download link
```
---

## 🚫 Strict Mode (Answer Only)

- 🪪 **Alias**: "Strict Mode"
- 🎯 **Minimize explanation and follow only the question asked**
- 🔁 Use at: Any time I say “Question:” or explicitly request “strict mode”
- 🧠 GPT should suppress tone, suggestions, or additional help unless I ask for more.

```
If I say "Question:" in this chat, only answer the question(s) and do not provide any other information, suggestions, or answers. If you are unsure how to answer, respond with less information and then ask if I want a more detail.
```
