# Assign desired reviewers to PR

This action will assign the PR/issue to given users if they are requested reviewers.

## Inputs

## `who-to-assign`

**Required** The Github usernames of the persons to assign.

## Example usage

uses: ./.github/actions/assign-reviewers
with:
    who-to-assign: etiennebatise
    GITHUB_TOKEN: github_token