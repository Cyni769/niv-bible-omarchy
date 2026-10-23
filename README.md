# niv-bible-omarchy

A minimal, keyboard-driven terminal scripture reader (NIV) built with Python and `curses`, tailored for Omarchy / Arch Linux setups with adaptive theming and `fzf` fuzzy search.

---

## Features

- **Adaptive Theming:** Dynamically reads active colors directly from your Omarchy Foot palette (`~/.local/state/omarchy/current/theme/foot.ini`), falling back cleanly to ANSI terminals.
- **Verse of the Day:** Deterministic daily scripture card on the home screen based on the current date.
- **Fuzzy Search:** Instant full-text search across all 66 books powered by `fzf`.
- **Fast Scripture Navigation:** Clean reading view with centered gutters, chapter briefs, and smooth paging.
- **CLI Direct Query:** Query verses or search keywords directly from the command line without launching the full TUI.

---

## Prerequisites

- **Python 3.8+**
- **fzf** (for interactive fuzzy search):
  ```bash
  sudo pacman -S fzf