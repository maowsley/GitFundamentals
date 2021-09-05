# git remote
When working with git, a **remote** is any git repository that is not on the machine you're working on. The counterpart to this is **local**, or the machine that is being developed on.

Take GitHub for exmaple. White git is the technologu that allows you to create local repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that respository back down or share it with others.
**Note**: White the repositores (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.
### Adding a remote
A remote can be added with the `git remote add` command, followed by the name and location of the remote. This name is a local name, meaning it's your label and does not impace the acutal remote whatsoever.
```
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
### Removing a remote
A remote can be removed with the `git remote remove` command, followed by the name of the remote.
```
```
git remote remove origin
```
## Resources
- [Git Remote Documentation](https://git-scm.com/docs/git-remote)
---
[Back to home](../README.md)
