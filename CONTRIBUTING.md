# Contributing to AkuchiS projects

Thanks for taking the time — issues and pull requests are genuinely welcome.

These tools are built to be small, offline, and dependency-light on purpose. The
bar for any change is simple: **does it keep the tool honest, and would it still
run on a fresh machine with nothing installed?**

## Reporting a bug

Open an issue with:

- what you ran (the exact command) and what happened,
- what you expected instead,
- your OS and the tool version (`--version` where available),
- any error output (a paste is fine — these tools don't phone home, so we can't
  see anything you don't show us).

A failing example we can reproduce is worth more than a long description.

## Suggesting a feature

Open an issue describing the **problem** first, not just the solution. The most
useful requests explain the situation you're stuck in; the fix often writes itself
from there.

## Pull requests

- Keep them focused — one change per PR is easier to review and merge.
- Match the surrounding style; don't reformat unrelated code.
- If a project ships tests or a `selftest`, run it and keep it green.
- New dependencies are a hard sell — most of these tools are deliberately
  stdlib-only or zero-dependency. If you need one, say why in the PR.
- By contributing, you agree your work is licensed under the repository's license.

## A note on scope

Some repos are intentionally finished — they do one thing. If you're unsure
whether a change fits, open an issue before writing code and we'll figure it out
together. No wasted weekends.
