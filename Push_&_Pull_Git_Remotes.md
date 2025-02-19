level 1 - Push & Pull -- Git Remotes!

## 1: Push Main!

### steps
```
$ git clone
```
![image](https://github.com/user-attachments/assets/8d8b700b-822c-42c6-9b7c-c2dfc43aeb13)
## 2: Remote Branches

### steps
```
$ git commit

$ git checkout o/main

$ git commit

```
![image](https://github.com/user-attachments/assets/6cd5b084-ca6e-4dec-bf4b-44252df6c496)
## 3: Git Fetchin'

### steps
```
$ git fetch
```
![image](https://github.com/user-attachments/assets/444c7c1f-8d7b-46a9-ba27-525d870e77d8)

## 4: Git Pullin'

### steps
```
$ git pull
```
![image](https://github.com/user-attachments/assets/e161e80f-be9a-44e0-85e3-430e35902e4a)

## 5: Faking Teamwork

### steps
```
$ git fakeTeamwork main 2

$ git commit

$ git pull
```
![image](https://github.com/user-attachments/assets/c92b5429-d744-4fb1-b48c-79cd53d2c5e6)


## 6: Git Pushin'

### steps
```
$ git commit

$ git commit

$ git checkout main

$ git push

```
![image](https://github.com/user-attachments/assets/06badf3b-5d45-4ce4-ae6c-42d8cca6e6f4)

## 7: Diverged History

### steps
```
$ git fakeTeamwork 1

$ git commit

$ git pull --rebase

$ git push

```
![image](https://github.com/user-attachments/assets/afa44c0e-096d-4499-a920-22bddcb49414)
## 8: Locked Main

### steps
```
$ git branch -f main c1

$ git branch -f feature c2

$ git checkout feature

$ git push

```
![image](https://github.com/user-attachments/assets/1353f0cd-ff6c-48be-8212-8e135b62d0fb)

 
 
