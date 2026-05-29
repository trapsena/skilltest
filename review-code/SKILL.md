---
name: review-code
description: Reviews code files for syntax errors, typos, missing imports, and obvious logic mistakes. Use when a file was just edited or saved in VS Code, when the user asks for a quick code review, or when checking a code file before continuing work.
---

# Review Code On Save

## Quick Review

When this skill is triggered, inspect the changed file and look for:

- Syntax or parse errors
- Mismatched brackets, quotes, or indentation
- Missing or incorrect imports, exports, or package references
- Misspelled identifiers, wrong function names, or copy-paste mistakes
- Obvious logic errors introduced by the edit

## Review Workflow

1. Read the changed file first.
2. Identify the language and apply the relevant syntax rules.
3. If the file depends on nearby code, open only the minimum context needed.
4. Report concrete findings first, ordered by severity.
5. Include file paths and line numbers when available.
6. If nothing is wrong, say that clearly and mention any uncertainty that remains.

## Output Style

- Be concise and direct.
- Focus on actionable issues, not general commentary.
- If the user asks for a fix, propose the smallest safe edit.