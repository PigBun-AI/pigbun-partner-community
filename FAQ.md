# FAQ

## Is PigBun open source?

Not yet.

This public repository is for documentation, issues, discussions, roadmap, and release notes. The core runtime is private while the product is stabilizing.

## Why not open source everything now?

PigBun is changing quickly. Opening the full runtime too early would create a second job: maintaining an open-source project surface before the product itself is stable.

The current priority is reliability for early users.

## Does PigBun run in the cloud?

No. PigBun currently runs locally on your computer.

The browser is only the workbench. The runtime starts locally and opens a local page.

## Why does PigBun need Claude Code or Codex?

PigBun is a partner harness. It coordinates conversations, workstreams, state, tools, and execution context. Claude Code and Codex are execution layers that can actually operate on local projects and tools.

## Can I use PigBun without Claude Code or Codex?

You can install PigBun first, but real work requires at least one supported local executor to be ready.

## How do I update PigBun?

Use the in-app update check, or run the installer again:

```bash
curl -fsSL https://pigbunai.com/install.sh | bash
```

PigBun's main update path is the runtime, not a frequent DMG replacement.

## Where should I report bugs?

Open a GitHub Issue in this repository.

If the report includes secrets or private data, redact them before posting.

