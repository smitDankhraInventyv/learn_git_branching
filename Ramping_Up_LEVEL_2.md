# level 2 - Ramping Up

## 1: Detach yo' HEAD

### steps
```
git checkout c4
```
![l2_a](https://github.com/user-attachments/assets/5ddf035e-e370-47ec-bd46-2522db2dbec0)

## 2: Relative Refs (^)

### steps
```
git checkout bugFix^

```
![l2_b](https://github.com/user-attachments/assets/e89ac8cc-d99a-43c1-bd49-1ef1272532cd)


## 3: Relative Refs #2 (~)
### steps
```
git branch -f main c6
git checkout HEAD^1
git bbranch -f bugFix HEAD~1
git branch -f bugFix HEAD~1
```
![l2_c](https://github.com/user-attachments/assets/0c37e6b1-749f-40b7-8f2b-fb906ca2028a)


##  4: Reversing Changes in Git
### steps
```
git reset HEAD^1
git checkout pushed
git revert pushed
```
![l2_d](https://github.com/user-attachments/assets/6d35fc6c-e57a-4fa5-80a1-04fb88998c29)


