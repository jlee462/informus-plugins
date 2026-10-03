---
name: build-from-a-package
description: Build what an Informus Flow work package asks for, in the repository open in this Claude Code session, then note what was built back on the package. Use when the person asks to build, implement or work on a Flow package here.
when_to_use: "When the person says things like build the … package, implement this Flow package here, work on … from Flow"
---

This is the person's own work, in their own session, under their own permissions.

1. `get_package` for the package they name. Read the ask, the decision and the next step.
2. Say in two or three lines what you'll change, and what you won't. If the package is unclear or the
   change looks risky, ask before touching anything.
3. Build it the way this repository works (its CLAUDE.md and existing code). Prefer the smallest change.
   Run the repository's checks.
4. Don't commit, push or deploy unless they ask.
5. When it's done, offer to note it on the package with `add_note`: what changed, which files, which
   branch, and what's left. Use plain words, and add it only on their yes.
