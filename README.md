# gitignore-cheatsheet
## .gitignore Cheatsheet

1) Create file .gitignore

2) Add command to git:
`git add .gitignore`

## Examples

Ignore all files and subfolders [https://stackoverflow.com/a/5581995]
```
# Ignore all files. But .gitignore file is not ignore
*
!.gitignore
```

Ignore all pictures. But ZZZEmpty.png is not ignore
```
# Ignore all pictures in folder. But ZZZEmpty.png is not ignore
/js/characters/img/*
!/js/characters/img/ZZZEmpty.png
```
