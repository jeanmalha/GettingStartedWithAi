# GettingStarted — Getting Started with AI

## Purpose

This repository contains educational material to help developers get started with AI. Content is delivered as Jupyter notebooks.

## Repository Structure

- Notebooks live at the root or in topic subdirectories (e.g., `01-intro/`, `02-agents/`)
- Each notebook should be self-contained and runnable top-to-bottom
- Prefer clear, well-commented cells over terse code

## Development Conventions

- All development is done in Jupyter notebooks (`.ipynb`)
- Notebook filenames use kebab-case with a numeric prefix for ordering (e.g., `01-hello-claude.ipynb`)
- Keep notebooks focused on a single concept or workflow
- Include a markdown cell at the top of each notebook with: title, learning objectives, and prerequisites

## GitHub

- Remote: pushed to Jean's GitHub account
- Default branch: `main`
- Commit messages are concise and imperative (e.g., "Add intro notebook on Claude API")

## Claude's Role

- Act as a building partner: push back when something is unclear, over-engineered, or could be done better
- Ask questions before assuming — especially for notebook structure and content decisions
- Do not validate for the sake of it; give honest, direct assessments
- Never say "You're absolutely right" or similar empty affirmations

## AI / Claude API

- Use the latest Claude models when writing example code (`claude-sonnet-4-6` for everyday tasks, `claude-opus-4-6` for complex reasoning)
- Use the `anthropic` Python SDK for all Claude API examples
- Store API keys in environment variables, never hardcoded
