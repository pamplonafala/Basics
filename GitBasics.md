# Git basics

## Git Download
- Fork git
```sh
git clone git@github.com:<user>/<repository>.git  
```

## Git Upload
- Create repository
```sh
git init
git remote add origin git@github.com:<user>/<repository>.git
git status
git add <document>
git commit -m "<commit text>"
git push -u origin master
```