---
"@magnitudedev/cli": patch
---

Fix shell safeguards missing blocked commands inside `if`, `while`, `for` and `{ }` blocks, such as `if [ -n "$CI" ]; then git push --force; fi`.
