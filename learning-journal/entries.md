# Learning Journal

## Starting with Git history

Git commits are snapshots, so each commit should capture a useful, focused
change. Clear commit messages make the journal easier to follow later.

## Working with staged changes

The working tree contains edits, while the staging area selects the exact
changes for the next commit. I should review `git diff --staged` before
committing so the recorded snapshot matches my intent.

## Learning from branches

A branch lets me work on an entry independently. Merging it back preserves
that work in the main history, and the graph view helps me confirm where the
branch joined the main line.
