# level 2 - To Origin And Beyond -- Advanced Git Remotes!

## 1: Push Main!

### steps
```
$ git checkout main

$ git pull

Fast forwarding...

$ git checkout side1

$ git rebase main

$ git checkout side2

$ git rebase side1

$ git checkout side3

$ git rebase side2

$ git checkout main

$ git rebase side3

Fast forwarding...

$ git push
```
![image](https://github.com/user-attachments/assets/c9daf784-c498-4fe0-bf0f-8decd7487e6c)

## 2: Merging with remotes

### steps
```
$ git checkout main

$ git pull

Fast forwarding...

$ git merge side1

$ git merge side2

$ git merge side3

$ git push
```
![image](https://github.com/user-attachments/assets/fb9f718b-cdc0-41a8-86f2-3c1a58c7e4b7)
## 3: Remote Tracking

### steps
```
$ git checkout -b side

$ git commit

$ git branch -u o/main

local branch "side" set to track remote branch "o/main"

$ git pull --rebase

$ git push
```
![image](https://github.com/user-attachments/assets/e05c8eac-c1ca-4ee4-95d6-b728f8e09b45)
## 4: Git push arguments

### steps
```
$ git push origin main

$ git push origin foo
```
![image](https://github.com/user-attachments/assets/10025174-0754-486a-bf2a-8a255cb48cb8)
## 5: Git push arguments -- Expanded!

### steps
```
$ git push origin foo

$ undo

$ git push origin foo:main

$ git push origin main^:foo
```
![image](https://github.com/user-attachments/assets/b71a8a88-c931-413b-a2c9-0823bb435f47)
## 6: Fetch arguments

### steps
```
$ git fetch origin c3:foo

$ git fetch origin c6:main

$ git checkout foo

$ git merge main
```
![image](https://github.com/user-attachments/assets/490f6359-5fb4-48bf-a319-783c58b6102b)
## 7: Source of nothing

### steps
```
$ git push origin :foo

$ git fetch origin :bar
```
![image](https://github.com/user-attachments/assets/c7a61d5f-d440-4dfb-8020-16277a0d370a)
## 8: Pull arguments

### steps
```
$ git pull origin c3:foo

$ git pull origin c2:side
```
![image](https://github.com/user-attachments/assets/1e696d54-8b8c-4ae8-bfb4-dbd9cfeaef6a)








 
