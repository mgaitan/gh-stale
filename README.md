# gh-stale

`gh-stale` is a custom extension for the GitHub CLI that helps manage stale pull requests (PRs) in your GitHub repositories. It allows you to list or automatically close PRs that have not been updated for a specified number of days.


## Installation


```
gh extension install mgaitan/gh-stale
```

To list all PRs that have not been updated for 30 days, run the following command:

```
gh stale
```

To close all PRs that have not been updated for 30 days, run the following command:

```
gh stale --close
```

**Attention:** Currently it process one page at a time, so you may need to run it multiple times to process all PRs.


Run `gh stale --help` for more options.
