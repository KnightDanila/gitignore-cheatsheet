# gitignore-cheatsheet
## .gitignore Cheatsheet

1) Create .gitignore file in project folder

2) Add command to git:
`git add .gitignore`

## Examples

Ignore all files and subfolders [https://stackoverflow.com/a/5581995]
```
# Ignore all files. But .gitignore file is not ignore
/*
!.gitignore
```

Ignore all pictures in folder. But ZZZEmpty.png is not ignore
```
# Ignore all pictures in folder. But ZZZEmpty.png is not ignore
/js/characters/img/*
!/js/characters/img/ZZZEmpty.png
```

## Markdown-Cheatsheet
[https://github.com/KnightDanila/markdown-cheatsheet/]  



https://www.jamescoyle.net/how-to/1094-ignoring-files-in-git-with-gitignore  
https://github.com/github/gitignore
