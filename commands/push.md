# git push
When you have a [remote](./remote.md) set up you'll need a to begin to move [commits](./commits.md) to the remote.
This can be done with the `git push` command.

You can attach a name and branch to your command to specify where you're pushing to.
```
git push origin main
```
This command will push the **main** branch to the remote called **Origin**. This means any commmits that are in your local will be **pushed** to the remote.

### Upstream Tracking
Instead of including the name of the remote and the branch you're on everytime, you can set local branches to track and upstream branch.
This means you can tell the branch to push its assigned upstream remote branch by using the command `git push`.

Before doing so you'll need to use the `-u` or `--set-upstream` flag. This can be done on any `git push`.
```
git push -u origin main
```
or:
```
git push --set-upstream origin main
```
After this command is used, you can just use `git push` and it will function the same way.

## Resources
- [git push documentation](https://git-scm.com/docs/git-push)
---
[Back to Home](../Readme.md)
