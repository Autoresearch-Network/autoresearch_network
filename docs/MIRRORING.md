# Mirroring Policy

This repository is maintained as a scrubbed mirror.

- Target mirror: `Autoresearch-Network/autoresearch_network`
- Upstream commit history is not preserved in this mirror.
- Identity-bearing artifacts are scrubbed before each push.
- Commits are authored by `AutoresearchNetwork <argusprotocol@proton.me>`.

## Script

Run `scratch/mirror_autoresearch_network.sh` from the workspace root.

## Modes

- `MODE=incremental` appends clean commits on top of current mirror history.
- `MODE=reset` rebuilds a single-root commit and force-pushes it.
