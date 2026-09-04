# Security Policy

## Reporting a vulnerability

Please do **not** open a public issue for a security problem.

Use GitHub's private reporting — [Report a vulnerability](https://github.com/quayshell/quay/security/advisories/new) — or email **security@quayshell.com**.

Include what you found, how to reproduce it, and what an attacker could do with it. You'll get an acknowledgement within 72 hours.

## Scope

Quay is a native macOS app. It runs coding agents as child processes on your machine, stores per-identity configuration under `~/.quay/`, and keeps its own state in `~/Library/Application Support/Quay`. Issues in any of that are in scope, as are issues in the update path (Sparkle) and the licence activation path.

## Supported versions

The current release only. Quay updates in place via Sparkle.
