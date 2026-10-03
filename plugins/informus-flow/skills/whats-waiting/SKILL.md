---
name: whats-waiting
description: Show what's waiting on the person in Informus Flow, and help them pick what to do first. Use when they ask what's on their plate, what's waiting on them, or what needs a decision in Flow.
when_to_use: "When the person says things like what's waiting on me, what do I need to decide, what's on my plate in Flow"
---

Use the Informus Flow connector's `whats_waiting` tool. It answers for the signed-in person, in the
workspace they connected.

Then:

1. List what's waiting, most overdue first, one line each: the priority, what it needs from them, and
   how long it has waited.
2. If a few things are decisions Flow has already researched, say so: those are quick to clear.
3. Offer to open any one of them (`get_package`), and don't open more than they ask for.

If nothing is waiting, say that plainly. If the tool isn't connected, tell them to connect Informus
Flow (Settings → Connectors in Claude, or `/mcp` in Claude Code) and approve it in Flow.
