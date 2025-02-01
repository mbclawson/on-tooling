# tooling-setup
## Overview
This repo will be a quick and dirty dump of tooling setup and tips/ricks.  Think extensions to install, settings to modify etc.

Will most like be just a README but may contain actual eg vsc setting json(?) dumps in the future.

## VSC
### Extentions
- `mechatroner.rainbow-csv@3.16.0`
    - This extension adds color to CSVs, with each column getting its own color
    - Makes working with CSVs _somewhat_ usable
- `streetsidesoftware.code-spell-checker@4.0.34`
    - Adds spell-check functionality to your files.
    - Especially useful for comments.
- `shardulm94.trailing-spaces@0.4.1`
    - Probably one of my favorite extensions.
    - This highlights any trailing spaces with a red highlight.
    - Really useful for code hygeine
- `eamodio.gitlens@16.2.1`
    - I defnitely don't take advantage of all functionality,
    however this is a really useful tool to evaluate git history in a given file

### Themes
- You already know it's ~~turtles~~ [Popping and Locking](https://marketplace.visualstudio.com/items?itemName=hedinne.popping-and-locking-vscode) all the way down: `hedinne.popping-and-locking-vscode@2.0.11`

### Settings
- Trailing-spaces: Trim On Save
    - Note this feature has the potential to generate A LOT
    of extra changes in a PR/MR if whitespace hasn't been cleaned up before.
    - Still worth in it my opinion to enable this

## Other tools
