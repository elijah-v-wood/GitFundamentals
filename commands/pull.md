# git pull
Similar to [git push](./push.md), a `git pull` will interact with the remote repository.
Only this time it will **pull** the changes it does not have from the remote down to the local repository.

This means any commits that are made on the remote repository will be pulled down and added to the local repository.

This can be done by adding the remote name and branch name:
```
git pull origin main
```

If there is any upstream connection established, you can use `git pull` without specifying a remote or branch.

## Resources
- [Git Pull Documentation](https://git-scm.com/docs/git-pull)
---

[Back to Home](../README.md)
