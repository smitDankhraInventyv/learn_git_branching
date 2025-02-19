# level 5 - Advanced Topics

## 1: Rebasing over 9000 times

### steps
```
$ git checkout bugFix

$ git rebase main

$ git checkout C4

$ git rebase bugFix

$ git checkout C5

$ git rebase c4'

$ git checkout C6

$ git rebase c5'

$ git checkout C7

$ git rebase c6'

$ git branch -f side c6'

$ git branch -f another c7'

$ git branch -f main c7'
```
![l5_a](https://github.com/user-attachments/assets/c32bb146-a593-45dd-9d1a-3c57c98dc3f5)
## 2: Multiple parents

### steps
```
$ git branch bugWork

$ git checkout c2

$ git checkout bugWork

$ git branch -f bugWork c2

$ git checkout main

```
![l5_b](https://github.com/user-attachments/assets/e661b06e-c682-49b0-aa12-3a65895f2eef)
## 3: Spaghetti
### steps
```
$ git checkout one

$ git cherry-pick c4 c3 c2

$ git checkout main

$ git checkout two

$ git cherry-pick c5 c4 c3 c2

$ git branch -f three c2
```
![l5_c](https://github.com/user-attachments/assets/321670a9-b2b8-4504-9935-4052e30ea9bd)

 
