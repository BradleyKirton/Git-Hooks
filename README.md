# Git-Hooks
A collection of Tangent specific git hooks

## Python Hooks

### Black Code formatter
Black will format all Python files according to pep8 when commiting.

1. Ensure *black* is installed globally ```pip3 install black```
2. Copy *Python/pre-commit* into the *.git/hooks/* folder of your local project repo
3. Ensure the file is executable (eg: chmod)
