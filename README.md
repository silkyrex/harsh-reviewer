# Harsh Reviewer

A simple Cursor subagent prompt for strict code reviews.

This repo currently has two core docs:

- `harsh-reviewer.md` - the harsh reviewer subagent definition.
- `pre-flight.md` - a short checklist to run before coding.

## What this is for

Use this when you want feedback that is:

- direct and strict
- focused on smaller, simpler code
- focused on leverage (work that pays off more than once)
- focused on the few tests that matter most

## Quick Start

1. Open `harsh-reviewer.md`.
2. Copy the prompt into your Cursor subagent setup.
3. Run it after code changes to catch overbuilt solutions.
4. Run `pre-flight.md` before coding to keep scope small.

## Workflow Tip

Use both files together:

- Before coding: run the `pre-flight.md` checklist.
- After coding: run the `harsh-reviewer.md` review pass.

This keeps changes small and easier to maintain.
