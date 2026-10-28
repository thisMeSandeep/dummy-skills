---
name: react-review
description: Use when the user asks to review, audit, or check a React component or file for problems. Covers hooks rules, unnecessary re-renders, accessibility, and missing keys.
---

# React component review

## Steps

1. Identify the files to review. If the user did not name files, run `scripts/find-components.sh` to list candidates.
2. Read each file completely.
3. Compare the code against every item in `references/checklist.md`.
4. Report findings as a list, ordered from most serious to least serious.
5. For each finding, give the file name, the line number, the problem, and a corrected code example.

## Rules

- Do not change any files unless the user asks for fixes.
- If a file has no problems, say so in one sentence.