# git commit
the command `git commit` will take all tracked changes (items added with [git add](./add.md)) and package them up in what is a called a commit.

Commits come with commit messages that are required for each commit. You add a message to a commit command by using the `-m` flag follow by a message in qoutes.

A commit message _can_ be anything, but best practices dictates that you should use that message to indicate  the changes in the commit.

For example, if we have an application we're working on where we just built out the ability to register new accounts, then you might have some variation of the following:
```
git add .
git commit -m "Added Register functioniality"
```

Then when viewing the history of the git repository, you can pinpoint where the registration functioniality was added.

## Resources
- [Git Commit Documentation](https://git-scm.com/docs/git-commit)
---
[Back to Home](../readme.md)
