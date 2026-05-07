# Security and Privacy Notes

PigBun runs locally and can interact with powerful local tools. Treat it as software you are inviting onto your own computer.

## Current Trust Model

- PigBun runtime runs on your machine.
- Work happens through local tools such as Claude Code and Codex.
- Local workspace actions depend on the permissions of your user account.
- Credentials you give to PigBun should be treated as sensitive.

## What Not To Share Publicly

When reporting issues, do not post:

- API keys
- access tokens
- passwords
- private SSH keys
- customer data
- private repository URLs if they should stay private
- full logs containing secrets

Replace sensitive values with `[redacted]`.

## Reporting Security Concerns

For now, please open a GitHub issue with a minimal description and mark clearly that it is security-sensitive, but do not include secrets or exploit details publicly.

As the user base grows, PigBun will add a more formal private security reporting path.

