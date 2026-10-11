---
name: qa-r2-gh-auto-multi
description: Use when an agent needs to check the length of an IT ticket reply draft. Counts the words in the draft and, if it is over 120 words, writes a shorter version.
---

# Reply length check

1. Read the reply draft.
2. Count its words (scripts/count_words.py shows the method).
3. If it has more than 120 words, rewrite it under 120 words without dropping facts.
4. Do not invent facts that are not in the draft.

See references/style-guide.md for tone.
