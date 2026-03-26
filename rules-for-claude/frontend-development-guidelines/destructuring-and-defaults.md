---
description: Rules for object destructuring and default value assignment.
globs: "**/*.{js,ts,jsx,tsx}"
---
# Destructuring & Defaults

- If default set in destructuring (e.g., `{ a = [] }`), don't use `a || []` later.
- Destructure when object has >3 properties or is referenced multiple times.