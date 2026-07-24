# Upstream relationship

- **Upstream:** https://github.com/NousResearch/hermes-agent
- **Divergence (as of 2026-07-24):** +3 ahead / -8538 behind upstream default branch
- **Fork type:** Contribution/maintenance fork
- **Sync cadence:** Periodic; evaluate migrating to official upstream.

## StartupBros-specific delta

Fork carrying StartupBros CI/deploy fixes. Very stale vs upstream.

## Why this file exists

An org-wide audit on 2026-07-24 found that comparing only the *default* branch made
several forks look like zero-delta mirrors when they actually carried unmerged
StartupBros fixes on side branches. Any future fork-pruning pass must enumerate and
author-check **all** branches, not just default-branch ahead/behind.
