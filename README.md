# Ideogram Homebrew tap

Homebrew formula for the [Ideogram CLI](https://pypi.org/project/ideogram-cli/), a command-line
client for the [Ideogram API](https://developer.ideogram.ai).

```bash
brew install ideogram-ai/tap/ideogram
ideogram login
```

`brew upgrade ideogram` picks up new releases. The formula follows the newest `ideogram-cli`
release on PyPI: a workflow checks every hour, and moves the formula only after it builds from
source and passes its test.
