---
name: comment-and-explain-code
description: Adds helpful inline comments to a code file and writes a companion Markdown explanation file. Use when the user wants code annotated for readability, when a file needs an explanatory walkthrough, or when documenting code after edits.
---

# Comment And Explain Code

## Goal

Read a code file, add brief comments that explain non-obvious logic, and create a separate Markdown file that explains the file in plain language.

## Workflow

1. Open the target code file and understand its purpose.
2. Add only the comments that improve clarity.
3. Keep comments short, accurate, and close to the code they explain.
4. Avoid restating obvious syntax.
5. Write a companion Markdown file with:
   - the file purpose
   - the main sections or functions
   - the important logic or dependencies
   - any risks, assumptions, or confusing parts
6. If the user does not specify a location, place the Markdown file next to the source file.

## Commenting Rules

- Explain why something exists, not what every token does.
- Comment complex branches, data transformations, and side effects.
- Keep existing useful comments unless they are wrong or redundant.
- Do not over-comment simple declarations or self-explanatory code.

## Markdown Output

Name the explanation file clearly, such as `filename-explained.md` or `filename-notes.md`.

Use concise headings so the explanation is easy to scan:

- Overview
- Main Parts
- Important Details
- Notes

## Result

Return both deliverables:

- the updated code file with comments
- the new Markdown explanation file
