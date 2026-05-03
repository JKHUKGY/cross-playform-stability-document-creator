# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Environment

This project uses [mise](https://mise.jdx.dev/) to manage tools and tasks. Required tools (defined in `mise.toml`):
- Python 3.12
- uv (package manager)
- claude (latest)

## Common Commands

```bash
# Create virtual environment
mise run venv-create   # or: uv venv

# Install all dependencies (including dev/test/doc extras)
mise run inst          # or: uv sync --all-extras

# Remove virtual environment
mise run venv-remove
```

## Project

`cross-playform-stability-document-creator` — a cross-platform stability document creator. The project is in early initialization; architecture and structure will expand as development progresses.
