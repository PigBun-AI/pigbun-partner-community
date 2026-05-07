# PigBun Partner Community

PigBun Partner is a local AI partner system.

It is not another chat wrapper. The goal is simple: you entrust an ongoing goal to PigBun, and PigBun helps you keep moving it forward through partner chat, workstreams, local tools, and a browser workbench.

This public repository is the community home for PigBun Partner:

- Report bugs
- Ask questions
- Read installation notes
- Follow the roadmap
- Track known issues and releases

The core runtime is not open-sourced yet. This repository exists so early users have a visible place to gather, give feedback, and understand what is changing.

## Install

PigBun currently runs as a local Node runtime with a browser workbench.

```bash
curl -fsSL https://pigbunai.com/install.sh | bash
```

After installation, start PigBun with:

```bash
pigbun
```

The installer will:

- Check the local runtime requirements.
- Download the latest alpha runtime.
- Install the `pigbun` command.
- Start PigBun locally and open the browser workbench.

## What PigBun Is For

PigBun is designed for people who want to hand off ongoing work, not just ask one-off questions.

Current alpha focus:

- Chat with an AI partner that remembers the context of your work.
- Create workstreams for ongoing goals.
- Let workstreams continue separately from the main chat.
- Use local execution tools such as Claude Code and Codex.
- Review progress, decisions, and blockers in the browser workbench.

## Current Status

PigBun is in alpha.

It is usable, but you should expect rough edges:

- Installation and auto-update are still being hardened.
- UI wording and internationalization are still being refined.
- Claude Code and Codex behavior may differ across user machines.
- Some workstream flows may still need manual guidance.

If you hit a problem, please open an issue with logs and steps to reproduce.

## Helpful Links

- [Roadmap](./ROADMAP.md)
- [Known issues](./KNOWN_ISSUES.md)
- [Feedback guide](./FEEDBACK.md)
- [Changelog](./CHANGELOG.md)
- [FAQ](./FAQ.md)
- [Security and privacy notes](./SECURITY.md)

## Where To Give Feedback

Use GitHub Issues for concrete bugs:

- Installation failed.
- PigBun cannot start.
- Chat or workstream behavior is broken.
- Update checks do not find the latest version.
- UI text is confusing or untranslated.

Use GitHub Discussions for:

- Product ideas.
- Questions about how to use PigBun.
- Workflow examples.
- Longer feedback that is not a direct bug.

## Not Open Source Yet

PigBun's runtime code is currently private while the product is stabilizing.

The short-term priority is to make the product reliable for early users before turning it into a full open-source maintenance surface. Public documentation, issue tracking, roadmap, and release notes will stay here.

