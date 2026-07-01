---
description: Prohibition of aria-* attributes in templates.
paths:
  - "**/*.{vue,html,jsx,tsx}"
---
# No ARIA Attributes

- Do not use `aria-*` attributes (e.g., `aria-label`, `aria-hidden`, `aria-expanded`, `aria-checked`, etc.) in templates.
- CSS-based pseudo-elements and semantic HTML should be used instead for accessibility.
