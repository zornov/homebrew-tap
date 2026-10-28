# Zornov for Homebrew

[Zornov](https://zornov.com) is a free, open-source film studio: edit, grade, animate, build 3D worlds, compose the score and deliver, and let AI assistants do the same through MCP.

```bash
brew trust zornov/tap
brew install --cask zornov/tap/zornov
```

This installs `Zornov.app` and puts the `zornov` command on your PATH, so Claude Code, Codex and other MCP clients can run `zornov mcp`. The app is signed and notarized, and needs an Apple Silicon Mac with macOS 13 or later. It updates itself from inside the app; `brew upgrade --cask zornov` works too.

Source, releases and docs: [github.com/zornov/zornov](https://github.com/zornov/zornov).
