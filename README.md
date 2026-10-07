# Hello GDX

A small repository for trying out edits and pull requests in a Codex cloud
environment.

## Getting started

Open the existing `hello-gdx` checkout and read this README. This repository
currently contains documentation only; no dependency installation, build, or
application startup is required.

## Example contribution

1. Create a branch for your change:
   ```sh
   git switch -c docs/update-readme
   ```
2. Edit this README to describe your change.
3. Review the diff and check for whitespace errors:
   ```sh
   git diff
   git diff --check
   ```
4. Commit and push the branch:
   ```sh
   git add README.md
   git commit -m "docs: update README"
   git push -u origin docs/update-readme
   ```
5. Open a pull request against `main`, describing what changed and how you
   checked it.

For a documentation change, a useful pull request description is:

> Replace the placeholder README with a project introduction and an example
> contribution workflow. Reviewed the README and ran `git diff --check`.
