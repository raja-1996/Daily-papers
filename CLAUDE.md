# CLAUDE.md

## Project Structure

- `papers/` — Topic-level markdown files, each covering a research theme
- `README.md` — Index of all topic files with paper counts and search queries

## Rules

- **Never create day-level or date-based markdown files** (e.g., `arxiv-recsys-report-2026-03-08.md`). All papers must go directly into the relevant topic file under `papers/`.
- When adding new papers, find the best matching topic file in `papers/` and append the paper to its table.
- If no existing topic fits, create a new topic file under `papers/` and add an entry to the README table.
- Update the paper count in `README.md` when adding papers.

## Paper Entry Format

Each topic file has a markdown table with these columns:

```
| Paper | Link | Key Details | Date | Company/Institution |
```

- Use `⭐` for landmark/deployed-at-scale papers, `🔥` for notable papers.
- Link format: `[arXiv:XXXX.XXXXX](https://arxiv.org/abs/XXXX.XXXXX)`
- Date format: `YYYY-MM`
- Use `—` when company/institution is unknown.
