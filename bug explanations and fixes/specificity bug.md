### Exercise 11 — CSS specificity

**Bug:** The paragraph remained red even though the blue class rule appeared later in the stylesheet.

**Cause:** The ID selector `#specificity-text` has higher specificity than the class selector `.class-style`. Therefore, the ID's red declaration won.

**Fix:** I removed the unnecessary ID-based color rule and kept the class-based rule. The text became blue without using `!important`.

**Lesson:** Prefer reusable class selectors for styling. Avoid using IDs for ordinary visual styling when a class can do the job.

**Evidence:** `specificity conflict bug.png` and `specificity conflict bug - fixed.png`.
