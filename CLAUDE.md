# CLAUDE.md

## Project Overview

This repository (`doublemkt/teste`) contains documentation and setup instructions for **notebooklm-py**, a Python package that provides programmatic access to Google's NotebookLM.

## Repository Structure

```
.
├── README.md    # Project README with installation instructions
├── claude        # Plain-text installation reference
└── CLAUDE.md    # This file
```

## Tech Stack

- **Language:** Python
- **Package:** `notebooklm-py` (installed via pip)
- **Optional dependency:** Playwright + Chromium (for browser-based login)

## Setup & Installation

```bash
# Basic install
pip install notebooklm-py

# With browser login support (required for first-time setup)
pip install "notebooklm-py[browser]"
playwright install chromium
```

## Git Workflow

- **Default branch:** `master`
- Commits should have clear, descriptive messages
- Push feature branches with `git push -u origin <branch-name>`

## Conventions

- Keep documentation concise and focused on installation/usage
- The `claude` file mirrors the install commands from `README.md` for quick reference
