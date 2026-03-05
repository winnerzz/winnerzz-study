# CLAUDE.md

This file provides guidance for AI assistants working on this repository.

## Project Overview

**winnerzz-study** is a Chinese-language documentation project aimed at capturing the essence of AI development — extracting the core thread of technological progress from the rapidly expanding landscape of AI concepts and terminology.

**Primary audience**: Chinese-speaking readers learning about AI
**Primary language**: Chinese (中文) for all content; English permitted in code, filenames, and technical identifiers

## Repository Structure

```
winnerzz-study/
├── CLAUDE.md       # This file
├── README.md       # Project introduction and table of contents
└── LICENSE         # MIT License
```

This is an early-stage documentation repository with no source code, build system, or test suite.

## Planned Content (from README)

The project intends to cover:

1. **AI发展的历史阶段** — Historical stages of AI development
2. **常用AI名词词典** — Common AI terminology dictionary

As the project grows, new content files (Markdown) should be added under appropriately named directories or as top-level `.md` files, reflecting the table of contents in `README.md`.

## Development Conventions

### Language & Writing Style
- All documentation content must be written in **Simplified Chinese (简体中文)**
- Maintain a clear, educational tone accessible to readers new to AI
- Technical terms may retain their English form on first use, with a Chinese explanation: e.g., `Transformer（变换器）`
- Avoid jargon-heavy phrasing; prefer plain language explanations

### File & Directory Naming
- Use lowercase, hyphenated English names for files and directories: e.g., `ai-history.md`, `terminology/`
- Each major section in the README table of contents should correspond to a file or directory

### Markdown Formatting
- Use `#` for the document title, `##` for major sections, `###` for subsections
- Add a blank line between sections for readability
- Code blocks should specify language: ` ```python `, ` ```bash `, etc.
- Keep lines under 120 characters where possible

### README Maintenance
- `README.md` serves as the single source of truth for the project description and table of contents
- Update the table of contents whenever new content files are added
- Keep the project description (lines 2–3) accurate and concise

## Git Workflow

### Branching
- **Main branch**: `master` — stable, reviewed content only
- **Feature/work branches**: `claude/<description>-<id>` for AI-assisted work; descriptive names for human contributors
- Never push directly to `master` without review

### Commits
- Write commit messages in **English**
- Use the imperative mood: `Add AI history overview`, `Update terminology entry for LLM`
- Keep the subject line under 72 characters
- Reference the section or file changed when helpful

### Push
```bash
git push -u origin <branch-name>
```

## No Build / Test System

This project currently has **no build system, package manager, or test suite**. There are no commands to run. If scripts or tooling are introduced in the future, document them here.

## License

MIT License — Copyright 2026 winnerzz. See `LICENSE` for details.
