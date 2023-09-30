# git commit

the command `git commit` will take all tracked changes (items add with [git add](./add.md)) and packages them up in what is called a commit.

Commits come with commit messages that are required for each commit. You add a message to a commit command by using the `-m` flag followed by a message in quotes.

a commit message _can_ be anything, but best practices dictates that you should use that message to inicate the changes included in the commit.

For example, if we have an application we're working on where we just built out the ability to register new accounts, then you might have some variation of the following:

```
git add .
git commit -m "Added register functionality"
```

Then when viewing the history of a git repository, you can pinpoint where the registration functionality was add.

## Resources

- [Git Commit Documentation](https://git-scm/docs/git-commit)

---
[Back to home](../README.md)