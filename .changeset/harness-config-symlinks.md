---
"@magnitudedev/cli": patch
---

Fix connecting or disconnecting a harness replacing a symlinked configuration file (for example `~/.config/opencode/opencode.json` linked from a dotfiles repo) with a standalone copy. Magnitude now writes to the file the link points at and leaves the link in place.
