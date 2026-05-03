# Class Seating Plan

A simple class seating-plan composer for teachers. Imports student names
and photos directly from a SEQTA class-roll PDF, generates randomised or
alphabetical layouts, supports separation rules between students, and
exports to PNG, CSV, or print.

## Use it

Open the live tool at:
**https://barrysv.github.io/seating-plan/**

No install, no account, no data leaves your browser.

## What it does

- **Imports SEQTA class rolls.** Print a class roll's "Student photos"
  view from SEQTA as a PDF, drop it in. Names, surnames, nicknames, and
  photos are extracted automatically.
- **Generates layouts.** Shuffle for a random arrangement that respects
  separation rules. Sort A–Z for alphabetical (cycle through four
  corners with each click).
- **Drag to refine.** Click and drag any student to swap with another.
- **Separation rules.** Define groups of students who must not sit
  adjacent. Violations are flagged live with a red badge.
- **Aisles, room reference, extra rows.** Set in the sidebar.
- **Export.** PNG (with adjustable font size), browser print, CSV, or
  full JSON layout backup.

## Use without the live link

If you'd rather have a local copy:
1. Download `seating-plan.html` from this repo.
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari).
3. Works offline once loaded.

## Privacy

Everything runs in your browser. No server, no database, no analytics.
Imported PDFs and student photos never leave your machine. Save/Load
uses local JSON files you choose where to store.

## Built by

Barry Vayler. Feedback and ideas welcome — please get in touch via
GitHub Issues or email.

## Licence

MIT — see [LICENSE](LICENSE).
