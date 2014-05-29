Git-Tricks
==========

Collection of nifty git-tricks that makes everyday life better

---

#### Lazy push to non-upstream remote branch:
Problem: Pushing to non-upstream remote branch require a lot of writing.

Solution:
```shell
git config remote.<remote>.push <branch>[:<remote_branch>]
```

Lazy example:
```shell
git push heroku
# instead of:
git push heroku feature:master
```
