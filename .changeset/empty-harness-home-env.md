---
"@magnitudedev/cli": patch
---

Fix connecting Codex, Hermes, OpenClaw or Pi when `CODEX_HOME`, `HERMES_HOME`, `OPENCLAW_STATE_DIR` or `PI_CODING_AGENT_DIR` is set but empty. Magnitude wrote to the filesystem root (or the current directory for Pi) instead of the default location the harness itself uses.
