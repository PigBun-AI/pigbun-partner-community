# Known Issues

PigBun Partner is in alpha. These are known areas that may still be rough.

## Installation

- Some machines may not have Node, pnpm, Claude Code, or Codex installed.
- Shell PATH changes may require opening a new terminal before `pigbun` is available.
- If another PigBun backend is already running, startup may ask you to stop the previous process.

## Updates

- Runtime updates are the main update path.
- The public alpha manifest is served from:
  `https://pigbunai.com/releases/runtime/alpha/darwin-arm64.json`
- If an update is installed while PigBun is running, you may need to restart the `pigbun` process.

## Browser Behavior

- Chrome is currently the safest browser for testing.
- Safari may behave differently on some machines. If Safari hangs, try Chrome and include that detail in your bug report.

## Executors

- Claude Code and Codex depend on the user's local installation and login state.
- If the local executor is not ready, PigBun may start but will ask you to fix the execution environment before work can proceed reliably.
- Codex and Claude Code can produce different tool events and stream behavior; PigBun is normalizing this over time.

## Workstreams

- Workstream behavior depends on both PigBun's harness and the selected executor.
- Some tasks may need manual clarification before they split into useful sub-workstreams.
- Tool configuration for a workstream is still an alpha feature and may need a restart to take effect.

## UI Language

- Some technical wording may still appear in advanced areas or logs.
- If you see raw translation keys, please report the exact page and language.

