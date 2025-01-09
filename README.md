# CSS Specificity Bug
This repository demonstrates a common CSS bug related to specificity.  A more specific selector unintentionally overrides the styling defined by a less specific one. The `bug.css` file shows the problematic code, while `solution.css` provides a corrected version.

**Problem:** The intended styling is not applied due to a higher-specificity selector overriding it.

**Solution:** Adjust selector specificity by using more appropriate selectors or adding `!important` (use cautiously).