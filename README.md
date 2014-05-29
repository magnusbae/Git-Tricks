Git-Tricks
==========

Collection of nifty git-tricks that makes everyday life better

---

**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*


- [Lazy push to non-upstream remote branch:](#user-content-lazy-push-to-non-upstream-remote-branch)

---


#### Lazy push to non-upstream remote branch:
Problem: Pushing to non-upstream remote branch requires a lot of writing.

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
