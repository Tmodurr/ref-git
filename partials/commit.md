
##### Stage all changed files**
  ```git add *```

##### Commit staged files*
```git commit -m 'Message with Commit Message"```

##### If there is already a remote configured with the same name (fatal: remote origin already exists.), update the existing remote
```git remote set-url origin https://github.com/Dewberry/med-project-program-compliance.git```


##### Remove a git commit which has not pushed
###### IF you have NOT pushed your changes to remote, if you have multiple commits ahead of remote, execute as needed (rolls back per execution)
```git reset HEAD~1```
