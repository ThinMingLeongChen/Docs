# Documentations

## Git

```bash
# List branches
git checkout
# Create new local branche and switch
git checkout -b <branche-name>
# Push the new branche and commit changes to remote
git push origin <branch-name>
# Change branche
git checkout <branche-name>
# Delete local branche
git branch -d <branche-name>
# Delete remote branche
git push origin --delete <branche-name>
# Undo commit
git reset --hard <old-commit-id>
git push -f origin <branch-name>
```

## Split and merge files
```bash
# Splited large files in cmd
split -b <size kilobytes>k <file name> <file splited name>

# Merge splited files
cat <file name 1> <file name 2> <...> > <file name and extension>
```

## Visual studio code extensions

```txt
Markdown All in One
Docker
Vetur
ESlint
```
