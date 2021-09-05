# git commit
The comit `git commit` will take all tracked changes (items added with [git add](./Add.md)) and package them up in what is called a commit.
Commites come with commit message that are required for each commit. You add a message to commit commands by using the `-m` flag followed by a message in quotes.
A commit message _can_ be anything, but best practice disctates that you should use that message to indicate that changes included in the commit.

For example, if we have an application we're working on where we just built ou the ability to register new accounts, then you might have variation of the following.
```
git add .
git commit -m"Added register functionality"
```
Then when viewing the history of a git repository, you can pinpoint where the registration functionality was added. 

## Resources
- [Git Commit Documentation](https://git-scm.com/docs/git-commit))
---
[Back to home](../README.md)