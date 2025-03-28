# 📘 Learning Tracker
<!--
📌 LOGGING PROTOCOL FOR LEARNING_TRACKER FILES

📌 1. IF CURRENT DAY (ASK FOR TIMEZONE OR USE UTC) ALREADY EXISTS:
    ➤ Add additional concepts, notes, or reflections under that date

📌 2. IF IT’S A NEW DAY (ASK FOR TIMEZONE OR USE UTC):
    ➤ Append a new entry at the bottom of the file with a `---` to separate from previous days

📌 3. WEEKLY SUMMARY PROTOCOL:
    ➤ Weeks run from **Sunday to Saturday**  
    ➤ Insert each `📊 Week Summary` *after the last daily entry* for that week, separated by `---`  
    ➤ If 3 or fewer entries exist for a given week, ask if I want to wait and include those partial days in the **next week**.

📌 WEEK SUMMARY FORMAT:

    ## 📊 Week Summary — YYYY-MM-DD to YYYY-MM-DD

    - ✅ Concepts mastered
    - 🛠️ Struggles or breakthroughs
    - ♻️ Reusable patterns
    - 🧭 Suggestions for next week

📌 TEMPLATE FOR DAILY LEARNING ENTRY FORMAT:

## YYYY-MM-DD

### Task/Challenge (change to be descriptive)
- ⏱️ Duration: [optional time spent]
- 🎯 Confidence: [Low / Medium / High]

#### ✅ New Concepts Practiced:
- [Key ideas, techniques, or strategies learned or reinforced]

#### 🛠️ Strategy & Problem-Solving:
- [What I fixed, how I discovered the issue, insights from the fix]

#### ♻️ Reusable Patterns and Strategies:
- [Patterns or approaches that might work in similar problems or activities]

#### 📌 Notes:
- [Thoughts, struggles, improvements in thinking or approach]

#### 📈 Areas for Continued Practice:
- [Concepts that still felt shaky or required GPT support]

#### 🧭 Next Suggestions:
- [Follow-up problems, techniques to reinforce, or reminders for tomorrow/next task]

### Additional Task/Challenge (if multiple on same day)...
-->

---

# EXAMPLE ENTRY FOR PROGRAMMER LEARNING (delete after first real entry)

## 2025-03-27

### Array Manipulation
- ⏱️ Duration: 90 minutes
- 🎯 Confidence: High

#### ✅ New Concepts Practiced:
- Prefix sum (difference array) for efficient range updates
- Deferred computation via cumulative sum sweep
- Array marking strategy using +add at start and -add at end
- Efficient use of `itertools.accumulate` to compute final values

#### 🛠️ Strategy & Problem-Solving:
- Identified inefficiency in O(n × m) nested loop updates
- Used question-driven debugging to isolate bottlenecks
- Gradually restructured loop logic to achieve linear-time solution

#### ♻️ Reusable Patterns and Strategies:
- Range-based optimization using difference arrays
- Readable and efficient cumulative processing with standard library tools

#### 📌 Notes:
- Array manipulation problems can often be reduced to scan-based approaches
- When facing timeouts, reframe the update strategy rather than reaching for complex data structures

#### 📈 Areas for Continued Practice:
- Constructing two-phase greedy approaches from scratch
- Optimizing nested loops via scans or auxiliary arrays

#### 🧭 Next Suggestions:
- Reinforce greedy vs DP identification
- Practice string edits with symmetry or constraints
- Try alternative implementations of prefix-based logic

### Highest Value Palindrome
- ⏱️ Duration: 120 minutes
- 🎯 Confidence: Medium

#### ✅ New Concepts Practiced:
- Two-phase greedy palindrome rebuild
- Efficient digit maximization under budget
- Symmetric pair checking with max replacement

#### 🛠️ Strategy & Problem-Solving:
- Identified need to track changed indices
- Used deque to simulate efficient pair tracking
- Shifted from index sentinel to direct matching

#### ♻️ Reusable Patterns and Strategies:
- Greedy two-pass string transformation
- Change tracking via deque
- Palindrome rebuild with optional center update

#### 📌 Notes:
- Mostly clean code generated without help from GPT, strong debugging steps, and runtime remained O(n)
- Polished and improved Pythonic style with help from GPT

#### 📈 Areas for Continued Practice:
- Greedy design for programs

#### 🧭 Next Suggestions:
- Focus on something lighter or more creative to re-energize and prevent burnout

---

# START ENTRIES HERE
