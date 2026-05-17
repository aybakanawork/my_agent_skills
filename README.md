# My Agent Skills and Instructions

## Agents 

### Goal

State the goal of the project here

### Instructions

- Don’t assume. Don’t hide confusion. Surface tradeoffs.
- Minimum code. Nothing speculative.
- Touch only what you must.
- Define success criteria. Loop until verified.
- Generate documentation to docs folder ONLY!
- Create Date-prefixed subdirectories in docs folder!
- Do not create explainer documents, implementation plans, or summary markdown files unless specifically requested. Use the chat interface for all reasoning
- when multiple methods present themselves, ask questions. We can make design decisions together.
- If you need to maintain a state or plan, only use docs/scratchpad.md. Overwrite it for every new task rather than creating new files. Include assumptions you made!
- Make version-based planning where each version must implement a single testable feature which can be a single UI item or method.

### Suggested Instruction Set by Gemini

Integrity: Don’t assume. Don’t hide confusion. Surface tradeoffs immediately.

Scope: Minimum code. Nothing speculative. Read widely, but write narrowly—touch only what is essential.

Verification: Define success criteria before coding. Loop until verified by execution/test output, not just code logic.

Documentation: Generate documentation to docs/ folder ONLY using YYYY-MM-DD prefixed subdirectories.

Communication: No explainer docs or implementation plans in the file system. Use the chat for reasoning.

Collaboration: When multiple methods exist, pause and ask. We make design decisions together.

State Management: Use docs/scratchpad.md as the sole source of state. Overwrite it for every new task. Include a 'Current Task', 'Assumptions', and 'Open Questions' section.

Granularity: Follow version-based planning. Each version implements exactly one testable feature (e.g., one UI component or one method).
