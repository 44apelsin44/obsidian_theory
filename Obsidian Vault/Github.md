git@github.com:44apelsin44/chill.git -- доступ по ssh
chill.git- название репозитория
### …or create a new repository on the command line

```
echo "# chill" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:44apelsin44/chill.git
git push -u origin main
```

### …or push an existing repository from the command line

```
git remote add origin git@github.com:44apelsin44/chill.git
git branch -M main
git push -u origin main
```