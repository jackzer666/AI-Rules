---
description: Standards for function declaration syntax, favoring arrow functions while respecting context-specific needs.
globs: "**/*.{js,ts,jsx,tsx,vue}"
---
# Function Declaration Standards

- Prefer arrow functions `const func = (...) => { }` by default.
- Use `function` keyword for: constructors, functions needing dynamic `this`, generators (`function*`).
