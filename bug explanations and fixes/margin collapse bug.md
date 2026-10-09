### Exercise 12 — Margin collapse

**Bug:** Two adjacent block elements each had a vertical margin of `3rem`, but the gap between them was only `3rem`, rather than `6rem`.

**Cause:** In normal block flow, adjacent vertical margins can collapse. When both margins are positive, the larger margin determines the gap.

**Fix:** I changed the parent to a column Flexbox layout. Flex items' vertical margins do not collapse, so both `3rem` margins contribute to the space between the boxes.

**Evidence:** `margin collapse bug.png` and `margin collapse bug-fixed.png`.
