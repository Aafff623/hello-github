# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **GitHub learning and testing repository** for practicing GitHub workflows, Git commands, and development patterns. It serves as a playground for testing GitHub features and techniques.

## Key Topics Covered

Based on the study notes in `docs/shirp_github_note/`:

- **Git Fundamentals**: Repository structure, branching, merging, conflict resolution
- **GitHub Basics**: Repository creation, organization management, page deployment
- **Workflow Tools**: GitHub Desktop, IDEA Git integration, VS Code
- **Advanced Features**: Actions (CI/CD), Webhooks, REST API, GitHub Packages
- **Deployment**: GitHub Pages, Docker integration with Actions
- **Files**: LFS for large files, security features

## Project Structure

```
hello-github/
├── .claude/          # Claude Code configuration
├── docs/             # Study notes and documentation
│   └── shirp_github_note/  # PDF study materials (closed)
└── .git/             # Git repository
```

## Common Commands

| Task | Command |
|------|---------|
| Check status | `git status` |
| View logs | `git log --oneline` |
| Create branch | `git checkout -b <branch>` |
| Merge branch | `git merge <branch>` |
| Resolve conflicts | `git mergetool` |

## Repository Configuration

- **Permissions**: Git config modifications are allowed (see `.claude/settings.local.json`)
- **Notes**: This is a personal learning repository - refer to study notes for reference
