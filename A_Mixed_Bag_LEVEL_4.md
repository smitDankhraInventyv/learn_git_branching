# level 4 - A Mixed Bag

## 1: Grabbing Just 1 Commit

### steps
```
git rebase -i HEAD~3git branch -f main c4'
```
![l4_a](https://github.com/user-attachments/assets/f0f48dee-8d62-4679-bd64-115add0988cb)
## 2: Juggling Commits

### steps
```
git rebase -i HEAD~2
git rebase -i HEAD~1
git rebase -i HEAD~2
git branch -f main c3
git branch -f main c3''
```
![l4_b](https://github.com/user-attachments/assets/b093295f-0c0c-40bc-8df1-291f49f8470f)
## 3: Juggling Commits #2

### steps
```
git rebase -i HEAD~2
git rebase -i HEAD~1
git cherry-pick c3
git branch -f caption c3
git branch -f main c3
git branch -f main c3'
```
![l4_c](https://github.com/user-attachments/assets/2ec48c2a-72fb-4656-9aaf-32cb9367ccb1)
## 4: Git Tags

### steps
```
git tag v0 c1
git tag v1 c2
git checkout c2
```
![l4_d](https://github.com/user-attachments/assets/4b54df16-c14a-4484-908a-34c03f8d36e2)
## 5: Git Describe

### steps
```
git commit
```
![l4_e](https://github.com/user-attachments/assets/e05d3492-94d1-4775-b1f8-2ea248179d9a)
