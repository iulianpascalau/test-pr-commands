# Testing the `gh pr` commands

## Setup

Install `gh` & authenticate:
```
sudo apt install gh
gh auth login
```

## Create a PR
```
git checkout <branch>
gh pr create --title "Updated readme.md - testing" --body "Testing the 'gh pr' commands in a dummy PR"
```

## Handling checks

### Getting check status
```
gh pr checks <PR number>
```

## Merge PR
```
gh pr merge <PR number>
```