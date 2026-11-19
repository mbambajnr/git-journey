# Git journey

This is my practice repo for learning Git and GitHub. I created it while following tutorials and trying the commands myself. I use simple text files so I can focus on what happens when I save a change, create a branch, or merge work together.

## What I am practising

- Tracking files and checking what has changed.
- Staging changes and making commits.
- Reading the commit history to see how files have changed.
- Creating branches to practise changes separately.
- Merging branches and learning how to handle conflicts.
- Pushing local work to GitHub.
- Writing commit messages that explain the actual change.

## What is in the repo?

The files `one.txt`, `two.txt`, `three.txt`, `four.txt`, and `myFolder/three.txt` are practice files. Their contents are simple words and numbers that I change during the exercises. They are not parts of a finished application.

`.gitignore` tells Git to ignore `.DS_Store`, a file macOS creates automatically. It does not need to be tracked with the practice files.

## The basic workflow

For a small change, this is the process I am practising:

1. Check the current branch and working files with `git status`.
2. Edit a file.
3. Review the change with `git diff`.
4. Stage the file I want to include with `git add <file>`.
5. Commit it with a short message describing what changed.
6. Push the commit to GitHub when it is ready.

For example, after adding the number 44 to `four.txt`, a useful commit message is `Add 44 to four.txt`. It makes the history easier to follow than a message like `changed 44`.

## Branches and merge conflicts

I use branches to try changes away from the main branch, then practise bringing the work back together.

A merge conflict can happen when Git cannot combine changes automatically. I am learning to read both versions, decide what the file should contain, remove the conflict markers, and check the result before committing.

Some of the practice files may still contain text from these exercises. A successful merge command does not replace checking the actual file contents.

## Lessons from feedback

My mentor pointed out a few things to improve:

- Keep macOS system files out of the repo.
- Make commit messages short and specific.
- Describe the change that was actually made. Adding text to a practice file is not the same as building a dark mode interface.
- Use a consistent Git author name and email so commits link to the right GitHub account.
- Explain the purpose of the repo in a README.

I have added an ignore rule for `.DS_Store`, set a GitHub-linked author identity for this repo, and corrected the misleading dark mode commit message. Some earlier messages are still vague, so they are a reminder of what I need to do better in future commits.

## What I want to get more comfortable with

I want to keep practising branches, checking changes before committing, and resolving conflicts carefully. The aim is to understand what each command does and build good habits as I learn.
