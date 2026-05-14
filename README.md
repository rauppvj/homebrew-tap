# rauppvj's Homebrew tap

Third-party Homebrew tap with casks for macOS utilities I maintain.

## Available casks

- [`clawdbar`](Casks/clawdbar.rb) — native macOS menu-bar app showing live Claude Code usage. Source: [rauppvj/clawdbar](https://github.com/rauppvj/clawdbar).

## Install

```bash
brew install --cask rauppvj/tap/clawdbar
```

Homebrew expands `rauppvj/tap` to `github.com/rauppvj/homebrew-tap`. The `homebrew-` prefix is what makes this repo recognizable as a tap.

If you'd rather tap first and then install (handy when more casks land here later):

```bash
brew tap rauppvj/tap
brew install --cask clawdbar
```
