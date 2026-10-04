# Versioned Learning Journal

This journal records Git learning notes as a sequence of meaningful commits.

## Inspecting the history

From the repository root, run:

```sh
git log --oneline --all --graph
```

The commit messages describe each journal update. The graph also shows the
`journal-entry` branch and its merge into `main`. To inspect the journal at a
particular commit, use `git show <commit>:learning-journal/entries.md`.
