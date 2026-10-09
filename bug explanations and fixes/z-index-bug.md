### Exercise 10 — Stacking context and z-index

**Bug:** The red child had `z-index: 9999`, but it still appeared behind the blue parent, which had `z-index: 2`.

**Cause:** Parent A had `position: relative` and `z-index: 1`, creating a stacking context. The child's z-index was only compared within that context, so it could not appear above a sibling stacking context with a higher stacking order.

**Fix:** I increased Parent A's z-index from `1` to `3`. This moved the entire parent stacking context above Parent B's stacking context, allowing the red child to appear in front.

**Evidence:** `z-index-bug.png` and `z-index-bug-fixed.png`.
