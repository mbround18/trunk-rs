# [Trunk by thedodd](https://github.com/thedodd/trunk)

This is an action wrapping the trunk binary for GitHub Action usage.

## Disclaimer

All work and credit goes to the original creators of the trunk project. This is merly a little bit of shell code that installs it from their github repo and adds it to path. Any issues with the action please file them here but any issues with trunk itself please log them on their github repo.

[Having trunk issues or questions? Click here to navigate to Trunk by thedodd's github repo.](https://github.com/thedodd/trunk)

## Usage

```yaml
# This is an example pipeline
name: Release
on: [push]
jobs:
  release:
    runs-on: ubuntu-latest
    steps:
      - name: Install Trunk
        uses: mbround18/trunk-rs@v1.0.0
```
