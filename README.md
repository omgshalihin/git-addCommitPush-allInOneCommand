# Git All-In-One Command
Put all git add, git commit, git push command in a makefile.

- within the project's root directory
```
touch makefile
```
- within the file, add the following commands (note: those are **tabs** not spaces)
```
git:
  git add .
  git commit -m "$m"
  git push -u origin main
```
- when you are ready, use this command in your CLI
```
make git m="<your message>"
```

### Now, you don't have to manually type them individually. Try it! 
