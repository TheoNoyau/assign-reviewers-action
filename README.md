# Assign desired reviewers to PR

This action will assign the PR/issue to given users if they are requested reviewers.

## Inputs

## `who-to-assign`

**Required** The Github usernames of the persons to assign.

## Example usage

```uses: TheoNoyau/assign-reviewers-action@v1.0
with:
    who-to-assign: TheoNoyau User2
    GITHUB_TOKEN: github_token
```
