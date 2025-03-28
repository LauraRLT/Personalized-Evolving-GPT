# 🧠 Solution & Reference Archive

This file stores reusable outputs, snippets, concepts, or reflections worth keeping across sessions.  
You (GPT) can suggest saving content here if:
- I confirm that something should be reused or saved
- A pattern, solution, or idea comes up that I may want to reference again
- We finish a difficult or novel challenge and I want to preserve the final result

If this file gets long, offer to help organize by date, topic, or tags.

---

<!--  
📌 ARCHIVE ENTRY TEMPLATE

## 🧾 [Descriptive Title or Task Name]
🗓️ Date: YYYY-MM-DD  
🔖 Tags: [type, topic, file name, concept]

**Summary:**  
[Short summary of what this is, where it came from, and what it's for.]

**Context / Prompt (optional):**
[Paste relevant GPT prompt, user prompt, or task summary]

**Output or Solution:**  
\```language (if applicable)
[code block or written solution]
\```

**Reflection / Notes:**  
- [Why this is useful, how to adapt it, where it might apply again]

-->

---

# START ARCHIVE ENTRIES BELOW THIS LINE (delete after first real entry)

## 🧾 Refactor: Prefix Sum with Difference Array
🗓️ Date: 2025-03-27  
🔖 Tags: python, prefix sum, performance, refactor

**Summary:**  
Refactored an O(n × m) loop using a difference array and prefix scan. Achieved linear performance.

**Output or Solution:**  
```python
def apply_operations(nums, ops):
    diff = [0] * (len(nums) + 1)
    for start, end, val in ops:
        diff[start] += val
        if end + 1 < len(diff):
            diff[end + 1] -= val
    for i in range(1, len(diff)):
        diff[i] += diff[i - 1]
    return [nums[i] + diff[i] for i in range(len(nums))]
```

**Reflection / Notes:**  
- Can adapt this for range increment problems
- Would be good to pair with a visual diagram or flow next time

---

# START ARCHIVE ENTRIES BELOW THIS LINE
