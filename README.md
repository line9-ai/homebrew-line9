# homebrew-line9

Homebrew tap for **line9** — diagrams for thinking. See <https://line9.ai>.

## Install

```sh
brew install line9-ai/line9/line9
```

Or tap first, then install by the short name:

```sh
brew tap line9-ai/line9
brew install line9
```

Homebrew strips the macOS Gatekeeper quarantine attribute on install, so the
binary runs with no "unidentified developer" prompt.

## Maintenance

`Formula/line9.rb` is generated from `line9-web`'s release workflow
(`scripts/update-homebrew-formula.sh`). Auto-update PRs against this tap are a
planned follow-up; until then the formula is updated manually per release.
