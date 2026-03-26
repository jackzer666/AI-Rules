---
description: Standards for async keyword usage and asynchronous flow control.
globs: "**/*.{js,ts,jsx,tsx}"
---
# Async Usage Standards

- Only use `async` keyword when function contains `await` or returns a Promise.
- Prefer `async/await` over `.then().catch()` for readability.