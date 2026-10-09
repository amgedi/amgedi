# Security

This repository is primarily a GitHub profile README, SVG assets, and the contribution-garden workflow. It does not store application user data.

If you find a security problem in the workflow, generated assets, or repository configuration, please report it privately through the repository **Security** tab when private vulnerability reporting is available.

Do not post credentials, tokens, private keys, exploit payloads, or private account information in a public issue.

The main security boundary here is the GitHub Actions supply chain. External actions used by the contribution-garden workflow are pinned to exact commits, and Dependabot is configured to surface GitHub Actions updates for review.

If a secret is ever committed accidentally, removing it from the latest commit is not enough. Revoke or rotate it immediately, then clean the repository history if needed.
