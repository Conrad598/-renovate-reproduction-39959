# 39959
Reproduction for [Renovate discussion 39959](https://github.com/renovatebot/renovate/discussions/39959).

## Current behavior

Renovate tries to pin the dependency despite the `"rangeStrategy": "bump"` config.

## Expected behavior

Renovate should bump the dependency, retaining the caret.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/39959