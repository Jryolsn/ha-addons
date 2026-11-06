# Agent notes

- Purpose: Home Assistant add-on repository. One folder per add-on (game servers and other services), each with `config.yaml`.
- The add-ons only reference public container images (ghcr.io/jryolsn/<name>); no application code lives here.
- Bump `version` in an add-on's `config.yaml` to make Home Assistant offer an update.
- Each add-on uses its own host port (8080, 8081, ...) and, if public, its own tunnel hostname.
- Status: see STATUS.md. Commits and PRs in English, no AI traces.
