---
name: Add a package
about: Request that a package be added to the viralemergence R universe
title: Please add [XXX] to the R universe
labels: Add Package
assignees: ''

---

Please provide the package name and a url for a git repo. 

```
{
        "package": "PACKAGE_NAME",
        "url": "https://github.com/USER_NAME/REPO_NAME" # can be any hosted git repo
 }
```

If your package is contained within a subfolder in your repo or you need to specify a particular branch to be used for the build, see additional information in the [R-universe docs](https://docs.r-universe.dev/publish/set-up.html#tracking-custom-branches-or-releases)
