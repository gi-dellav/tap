# gi-dellav/tap

Homebrew tap for [@gi-dellav](https://github.com/gi-dellav)'s projects.

## Install

```bash
brew tap gi-dellav/tap
brew trust gi-dellav/tap          # required on Homebrew 6.0.0+
brew install zerostack
brew install multistack           # depends on zerostack
```

Or fully-qualified (auto-trusts only that formula):

```bash
brew install gi-dellav/tap/zerostack
brew install gi-dellav/tap/multistack
```

## Packages

| Formula | Description |
|---|---|
| `zerostack` | Minimalistic coding agent — optimized for memory footprint and performance |
| `multistack` | Lightweight TUI for parallel agent management (depends on `zerostack`) |
