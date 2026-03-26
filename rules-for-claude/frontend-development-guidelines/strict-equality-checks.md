---
description: Standards for equality operators (===) and legacy code preservation.
paths:
  - "**/*.{js,ts,jsx,tsx,vue}"
---
# Strict Equality Checks

- Always use `===` and `!==` in new code. `==` and `!=` are forbidden.
- Do not auto-convert legacy `==`/`!=` to `===`. Only update when refactoring surrounding logic.
