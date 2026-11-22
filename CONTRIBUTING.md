# Contributing

Thanks for taking the time to help. This repository is a personal home lab write-up, so the most useful contributions are:

- **Corrections**: a technical error, a broken command, an outdated step, a wrong VLAN or firewall rule.
- **Clarity fixes**: typos, broken links or an explanation that could be clearer.
- **Suggestions**: resources, labs or better ways to build or secure something.

## How to contribute

1. **Open an issue first** using one of the issue templates, so the change can be discussed before you spend time on it.
2. **Fork the repository** and create a branch with a short, descriptive name (for example `fix-vlan-table`).
3. **Keep changes small and focused**: one fix or topic per pull request.
4. **Open a pull request** and fill in the pull request template.

## Style

- Write in Markdown with clear headings.
- Put commands and output in fenced code blocks with a language tag (for example ` ```bash `).
- Use placeholders such as `<subscription-id>`, `<tenant-id>`, `<password>` and `<your-ip>` instead of real values.
- Use private address ranges (`10.0.0.0/8`, `172.16.0.0/12`, `192.168.0.0/16`) or documentation ranges (`192.0.2.0/24`) in examples.

## Never include

- API keys, passwords, tokens, connection strings, SAS tokens or private keys.
- Azure subscription IDs, tenant IDs, or public IPs and hostnames of real resources.
- Personal information about yourself or anyone else.
- Unredacted screenshots of portals, consoles or work systems.

Pull requests that contain any of these will be closed. If you accidentally commit a secret, revoke it right away. Deleting it from the file is not enough, because it stays in git history.

## Code of Conduct

By taking part, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
