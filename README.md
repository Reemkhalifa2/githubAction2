# Commit Message Lint

## Implementation

Implemented a GitHub Actions workflow that checks commit messages on every push to `main`.

## How it works

* First push → checks last commit
* Other pushes → checks all new commits

## What does it check?

* Allowed types: fix, feat, docs, style, refactor, test, chore, perf, revert
* Message must be lowercase (not uppercase or capitalized)

## Purpose

Ensure all commit messages are clean and consistent.
