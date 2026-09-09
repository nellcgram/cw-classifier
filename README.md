# cw-classifier

Content-warning and intensity classification for fiction, built as a
prompt-engineering and evaluation project.

## Content note

This project classifies fiction for depictions of sexual assault,
self-harm, child abuse, suicide, eating disorders, and graphic
violence, including invented example sentences used to test the
classifier. The subject matter is inherent to the project's purpose.
See `spec/tags-v1.md` and `findings/` for the categories and reasoning.

## Status
Week 1 — repo scaffolding. No results yet.

## Layout
- `spec/` — the classification spec, versioned
- `skill/` — SKILL.md
- `evals/cases/` — trigger sets and test cases
- `evals/runs/` — graded runs, one file each
- `scripts/` — grading and tally scripts
- `findings/` — defects found in the spec, rubric, or harness