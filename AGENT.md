# Agent notes

- Purpose: Home Assistant add-on repository. One folder per game server, each with `config.yaml`.
- The add-ons only reference public container images (ghcr.io/jryolsn/<game>); no game code lives here.
- Bump `version` in an add-on's `config.yaml` to make Home Assistant offer an update.
- Each game uses its own host port (8080, 8081, ...) and its own tunnel hostname.
- Status: see STATUS.md. Commits and PRs in English, no AI traces.
