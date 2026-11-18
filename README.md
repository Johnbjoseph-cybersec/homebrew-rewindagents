# homebrew-rewindagents

Homebrew tap for [rewindagents](https://github.com/Johnbjoseph-cybersec/rewindagents): undo for AI coding
agents, including `rm -rf` and other shell commands.

```sh
brew install johnbjoseph-cybersec/rewindagents/rewindagents
rewindagents --version
```

The formula installs the same package as `pipx install rewindagents` from PyPI into its own virtualenv. Its
source of truth is `packaging/homebrew/Formula/rewindagents.rb` in the main repository. CI in this repository
installs and tests the formula on macOS and Linux on every push.

Apache-2.0.
