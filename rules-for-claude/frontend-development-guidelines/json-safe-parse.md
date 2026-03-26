---
description: Safe JSON parsing standards using try-catch blocks.
globs: "**/*.{js,ts,jsx,tsx,vue}"
---
# Safe JSON Parsing

- Wrap `JSON.parse()` in `try...catch` to prevent crashes.
- Consider utility function `safeJsonParse(str, defaultVal)` for reuse.