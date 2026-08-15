# OpenX123 Homebrew Tap

Homebrew Casks published by OpenX123 release workflows.

## Codex Taskboard

After a signed and notarized Codex Taskboard release passes its install lifecycle:

```bash
brew install --cask openx123/tap/codex-taskboard
taskboard setup
```

The Cask is generated from the immutable GitHub Release asset, pins its SHA-256,
and is updated only after the app, updater, Gatekeeper, and Homebrew smoke tests
pass. Uninstall keeps Taskboard user data by default.

Codex Taskboard is an unofficial companion for Codex and is not affiliated with
or endorsed by OpenAI.
