# Security Policy

## Scope

This repository contains documentation, sanitized configs and scripts for an isolated home lab. It holds no production systems or real user data. Security issues that matter here include:

- An exposed credential: API key, password, token, connection string, SAS token or private key, anywhere in the files or commit history.
- Exposed personal or identifying information, including in screenshots.
- A command, script or configuration that is unsafe to run as written (for example one that opens a system to the internet or disables security controls without warning).
- A malicious or compromised link.

## Reporting a vulnerability

**Please do not open a public issue for security problems.**

Report privately through GitHub:

1. Go to the repository's **Security** tab.
2. Click **Report a vulnerability**.
3. Describe what you found, where (file, line or commit) and why it is a risk.

You can expect an acknowledgment within 7 days. Confirmed issues will be fixed, and any exposed credential will be revoked and rotated, not just deleted.

## Supported versions

Only the latest version on the `main` branch is maintained.
