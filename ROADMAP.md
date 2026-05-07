# Roadmap

This roadmap is intentionally practical. PigBun is still in alpha, so stability and feedback quality matter more than adding more surface area.

## Now

### Reliable Local Runtime

- Keep the `pigbun` command install path simple.
- Make runtime updates visible and reliable.
- Improve startup recovery when a previous backend is still running.
- Make browser compatibility predictable, especially Safari and Chrome.

### Clear Product Language

- Replace technical wording with user-facing language.
- Keep executor, runtime, MCP, and CLI details out of normal screens.
- Improve Chinese, English, and Russian translation coverage.
- Make onboarding feel like "ready to work", not "configure a tool".

### Workstream Reliability

- Keep main chat, workstreams, drawer, and meeting room on shared state contracts.
- Make "waiting for user" visible and easy to answer.
- Improve tool-call rendering and activity status.
- Make executor switching safe across Claude Code and Codex.

## Next

### Feedback Loop

- Make it easier to export useful logs for bug reports.
- Add a simple issue template for install, update, chat, and workstream bugs.
- Document where local data and logs are stored.
- Create a lightweight feedback path for non-technical users.

### Operating Entrustment

- Treat every entrusted goal as a long-term responsibility, not a one-time task.
- Improve prompts and playbooks for delivery, deployment, monitoring, and follow-up.
- Add clearer patterns for when workstreams should split into sub-workstreams.
- Make deployment and operations more "done for you" by default.

### Tool Autonomy

- Let workstreams propose extra capabilities in a safer flow.
- Keep PigBun's built-in control tools isolated from user-added tools.
- Make broken external tools recoverable without breaking PigBun itself.

## Later

- Public API or extension contracts.
- More executor adapters.
- Better launcher experience for users who do not like terminal commands.
- Stronger community examples and templates.
- Possible selective open sourcing of installer, launcher, protocol docs, or SDK components.

## Non-goals For Now

- Full SaaS platform.
- Heavy multi-user collaboration.
- Complex admin panels.
- Turning every internal runtime concept into a user-facing setting.
- Open-sourcing the full core runtime before the product is stable.

