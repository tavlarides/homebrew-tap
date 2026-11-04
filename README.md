# Homebrew tap

Homebrew casks maintained by [tavlarides](https://github.com/tavlarides).

## Install Tasevka

```sh
brew tap tavlarides/tap
brew install --cask tavlarides/tap/font-tasevka
```

Includes the Tasevka font files available in the selected release, in normal and
extended widths with upright and italic styles. Future releases may add families.

Font source, build configuration, licenses, and releases:
[custom-iosevka-nerd-font](https://github.com/tavlarides/custom-iosevka-nerd-font).

## Update

After publishing a new font release, run from the font source repository:

```sh
PYTHON=python3 ./homebrew/update-tap.sh
```

The script generates the cask from the release archive, calculates its checksum,
and commits and pushes the update to this tap.
