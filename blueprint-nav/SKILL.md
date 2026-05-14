---
name: blueprint-nav
description: Uses the .kiro/ARCHITECTURE.md map to find logic without crawling.
---

# Skill: Blueprint Navigation

## Guidelines
- **The Golden Rule:** You are NOT allowed to use `ls -R` or `find`. 
- **Consult the Map:** Your first action for any task must be `cat .kiro/ARCHITECTURE.md`.
- **Targeted Entry:** Use the map to jump directly to the relevant directory.
- **Out of Date?** If you find a file mentioned in the map is missing, your first priority is to update `ARCHITECTURE.md`.

## Expected Behavior
1. Read `.kiro/ARCHITECTURE.md`.
2. Identify the specific sub-directory needed.
3. Only then, perform a local `ls` of that directory.