# CLAUDE.md — Gareth's PA

## What This Is

This is a prompt engineering project, not a code project. The main deliverable is `system-prompt.md` — a set of custom instructions that turn Claude into an ADHD-friendly personal assistant with 8 Goblin Tools-style features.

## File Structure

- `system-prompt.md` — THE deliverable. User copies this into a Claude Project's custom instructions.
- `tools/` — Individual reference docs for each of the 8 tools (design specs, not uploaded to Claude)
- `README.md` — User-facing setup guide
- `CLAUDE.md` — This file (repo context for Claude Code sessions)

## Design Principles

- **Mobile-first** — all output formats must work on a phone screen
- **ADHD-friendly** — short, scannable, no walls of text, always actionable
- **Minimal cognitive load** — the user should never have to think about HOW to use a tool
- **Menu-based navigation** — numbered menu, pick by number
- **Simplified detail control** — "more detail" / "less detail" (not a 1-5 scale)

## How to Test Changes

1. Copy the updated `system-prompt.md` content into a Claude Project
2. Start a new conversation in that project
3. Test each tool with sample inputs
4. Check: Is the menu clear? Is the output scannable on a phone? Does detail control work?
5. Test edge cases: overwhelm detection, "just start" mode, tool chaining
