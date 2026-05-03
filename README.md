# Excel Shortcuts & Functions Cheat Sheet

A personal, growing reference of Excel shortcuts, functions, and IB-specific techniques. Built up question by question — every time I learn a new shortcut, it gets added here.

## Live version

> Replace this once you deploy: `https://atraul.github.io/excel-cheatsheet/`

## What's inside

The cheat sheet is organized into four parts with a sticky sidebar TOC:

1. **Shortcuts** — Navigation, editing, formatting, view & audit, fill, rows & columns
2. **Functions & Formulas** — Lookups (VLOOKUP, INDEX/MATCH with animated demos), logical (IF, IFERROR, SUMIFS), financial (NPV, IRR, PMT), date, text, and common formula recipes
3. **IB Toolkit** — Color conventions, custom number formats, sensitivity analysis, three-statement linking, circular references
4. **Reference** — Common error codes and memory tips for ribbon shortcuts

Items most relevant to investment banking are tagged with a small **IB** badge.

## How to use

- **Locally:** double-click `index.html` to open it in any browser
- **Print:** Ctrl+P from the browser — the layout is print-optimized and the animated lookup demos freeze on the meaningful "match" frame
- **Updating:** open the file in VS Code (or any text editor) to edit the HTML directly, or ask Claude to add new shortcuts

## File structure

```
excel-cheatsheet/
├── README.md       this file
└── index.html      the cheat sheet itself (single self-contained file)
```

No external dependencies — the HTML, CSS, and animations all live inside `index.html`.

## Built with

HTML, CSS, and a lot of Excel curiosity. Authored with help from Claude.
