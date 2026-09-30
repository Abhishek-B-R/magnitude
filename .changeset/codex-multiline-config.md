---
"@magnitudedev/cli": patch
---

Fix connecting Codex when `~/.codex/config.toml` has a multi-line value with a line starting with `[`, which wrote the Magnitude settings into that value instead of the top level and left the previous model selected.
