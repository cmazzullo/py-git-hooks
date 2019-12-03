# Py-Git-Hooks

A few git hooks for Python development
- Automatically run flake8 on .py files
- Check for non-ascii characters
- Add the issue number (if any) in the branch name to the commit message
- Print the commits being pushed on push

# Installation

- Clone this repository: `git clone https://github.com/cmazzullo/py-git-hooks.git`
- Copy the git hooks into your local repository's `.git/hooks/` folder:
`cp pre-commit pre-push prepare-commit-msg /path/to/my/repo/.git/hooks/`

# TODO

- Add a hook that runs project tests before pushing
