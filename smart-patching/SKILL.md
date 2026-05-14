---
name: smart-patcher
description: Forces surgical code edits instead of full-file rewrites.
---

# Skill: Smart Diff & Patching
## Guidelines
- **Prohibit Full Output:** You are strictly forbidden from outputting the entire file content if the file is >50 lines.
- **Search and Replace:** Use the `sed` tool or a specific `patch` command if available.
- **Chunking:** If you must use a tool to write, provide only the specific function or block being changed.
- **Verification:** After a patch, run a targeted `grep` to verify the change instead of reading the whole file to "check your work."

## Output Format
- Use Unified Diff format (`---`/`+++`) when describing changes.