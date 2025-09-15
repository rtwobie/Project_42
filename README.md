# School 42 Projects

to clone:

```
git clone --recursive https://github.com/rtwobie/Project_42.git
git submodule foreach --recursive '(git checkout main || git checkout master) && git pull'
```

to update to latest commits + track main branches in all projects:

```
git submodule update --remote --recursive
git submodule foreach --recursive '(git checkout main || git checkout master) && git pull'
```
