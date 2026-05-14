---
name: search-optimizer
description: Specialized ripgrep wrapper to navigate code without reading full files.
---

# Skill: Token-Efficient Search
## Guidelines
- **No Blind Reading:** Never use `cat` or `read_file` on unknown files. Always `search` first.
- **Context Limits:** When searching, always use `-C 2` (2 lines of context) to save tokens.
- **Filtering:** If a search returns >15 results, you MUST refine the query with file extensions or directory excludes before reading content.
- **Structure First:** Prefer `ls -R` or `tree` (piped to `head`) to understand the tree before searching.

## Preferred Commands
- `rg --line-number --column --color never "query"`
- `rg -g "*.{ts,tsx}" "query"` (Scoped search)