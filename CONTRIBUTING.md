# Contributing to Release Ops Lab

Thanks for your interest in improving this sandbox!

This repository is a practice environment for release automation, so the barrier to entry is intentionally low. The rules below keep the sandbox tidy while still leaving room to experiment.

## How to contribute

1. Create a branch for your change (for example, `add-contributing-guide`).
2. Make your change and keep it small and self-contained.
3. Open a pull request into the default branch.
4. Let the `CI` workflow run and check the `build-report` artifact it uploads.

## Ground rules

- Keep commits atomic and messages descriptive.
- Don't break the `workflow_dispatch` trigger on `ci.yml` — the whole point of this lab is being able to start runs by hand.
- Prefer changes you can verify: trigger a run, inspect the artifact, and record the result on the `Rollout checklist` tracking issue.

## Reporting problems

Open an issue describing what you expected and what happened instead. This is a sandbox, so "expected" and "actual" can both be wrong — that's fine.
