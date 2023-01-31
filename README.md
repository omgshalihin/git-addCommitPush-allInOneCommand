# Makefile git add commit push github All in One command
### How to run ALL in one command from within a Makefile?
Put all git add, git commit, git push command in a makefile, In just 3 simple steps as follow:

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
