title: git-svn
tags:
---

```
git svn clone http://url/of/svn/repo test.svn
```

```
git init --bare test.git
```

```
cd test.svn
git remote add origin file://path/to/test.git
git branch --set-upstream-to=origin/master master
git push
```

```
git clone file:///path/to/test.git
git pull
```
