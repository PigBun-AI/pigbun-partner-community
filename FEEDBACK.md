# Feedback Guide

Good feedback helps us fix PigBun faster.

## For Bugs

Please include:

- What you were trying to do.
- What happened instead.
- Whether you were using Claude Code or Codex.
- Your operating system and browser.
- The PigBun version if you can see it.
- Relevant terminal logs.

Useful examples:

- "Install script finished, but `pigbun` command was not found."
- "Chrome opened, but the page stayed on waiting for backend."
- "I sent a message to the partner and the page went blank."
- "Check update still says no update, but I expected the latest alpha."
- "A workstream asked for input, but I could not find where to reply."

## For Product Feedback

Please describe the real workflow:

- What did you want to entrust to PigBun?
- Where did you expect PigBun to take over?
- Where did you still feel like you had to manage it manually?
- What would have made you trust it more?

PigBun is built around the idea of entrustment. Feedback about trust, clarity, and "does it feel like someone is helping me carry this?" is as important as technical bug reports.

## Logs

When reporting issues, terminal logs are often the most useful source.

Please remove secrets before sharing logs:

- API keys
- access tokens
- passwords
- private URLs
- customer data

If you are not sure whether something is sensitive, replace it with `[redacted]`.

