# Py-Git-Hooks

A few git hooks for Python development
- Automatically run isort and flake8 on .py files
- Check for non-ascii characters
- Print the commits being pushed on push
- Add the issue number (if any) in the branch name to the commit message.
Note: branches need to start with the issue number (e.g. 8704-fix_bug) for this feature to work.

## Installation

- Clone this repository: `git clone https://github.com/cmazzullo/py-git-hooks.git`
- Copy the git hooks into your local repository's `.git/hooks/` folder:
`cp pre-commit pre-push prepare-commit-msg /path/to/my/repo/.git/hooks/`

## TODO

- Add a hook that runs project tests before pushing
