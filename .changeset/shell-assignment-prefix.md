---
"@magnitudedev/cli": patch
---

Fix shell safeguards letting a blocked command through when it starts with an environment variable, such as `AWS_PROFILE=prod terraform destroy` or `CI=1 rm -rf /etc`.
