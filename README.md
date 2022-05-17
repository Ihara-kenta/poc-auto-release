# poc-auto-release

This Repository is [google-github-actions/release-please-action: automated releases based on conventional commits](https://github.com/google-github-actions/release-please-action) and [aslafy-z/conventional-pr-title-action: Ensure your PR title matches the Conventional Commits spec.](https://github.com/aslafy-z/conventional-pr-title-action) PoC.


## Concept

- Premise
	- We use [GitHub Flow – Scott Chacon](http://scottchacon.com/2011/08/31/github-flow.html) for git branch workflow.
	- We use **Squash and merge** as Merge Pull Requests option.
- Force Pull Request's title into [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) format.
- Automate tagging of semantic versioning.
    - create or update CHANGELOG.md

### release-please

cf. https://github.com/google-github-actions/release-please-action

### Check PR Title

cf. https://github.com/aslafy-z/conventional-pr-title-action
