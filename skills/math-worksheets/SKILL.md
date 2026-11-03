---
name: math-worksheets
description: Make printable math worksheets with answer keys (Pre-Algebra through Calculus) using the Sigma Prep Worksheets MCP server.
---

# Math worksheets with answer keys

Use the `sigma-prep-worksheets` MCP server when someone asks for a math worksheet, practice problems to print, or an answer key.

1. Call `search_worksheets` with the topic in plain words (for example "factoring trinomials" or "law of sines"). Add `course` to narrow it (for example "Algebra 2").
2. Call `create_worksheet` with the topic id it returns. Optional: `levels` (any of easy, medium, hard), `count` (up to 40 problems, default 20), `questionTypes`, and `version` to get the same sheet again.
3. Share both links: the student worksheet (PDF) and the copy with the answer key.

Every call makes a fresh set of problems, so a retake or a second class period gets a new sheet.
