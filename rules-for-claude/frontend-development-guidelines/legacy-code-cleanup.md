---
description: Rules for handling legacy, commented-out code and TODOs.
paths:
  - "**/*"
---
# Legacy Code Cleanup

- Always ask the user before deleting commented-out code. Never delete without permission.
- If code must stay, add `// TODO:` with version for cleanup (e.g., `// TODO: cleanup in v1.2`).