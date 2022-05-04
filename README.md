# [Trunk by thedodd](https://intuit.github.io/auto/docs)

This is an action wrapping the trunk binary for GitHub Action usage.

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
