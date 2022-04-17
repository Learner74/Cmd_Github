# Github Repo

![](https://camo.githubusercontent.com/76109812f3127b0f86940373897b04ac8943cb3c0f057f90046444480f61bafd/68747470733a2f2f692e696d6775722e636f6d2f77617856496d762e706e67?utm_source=pocket_mylist)

## To config Laptop With Github

```cpp
    1. //Findout the SSH
        ssh-keygen -t rsa -b 4096 -C "example@gmail.com"
    2. // then insert your Password
    3. // the serial for github is by
        cat ~/.ssh/id_rsa.pub
    4. //copied it and put in github
        [Github](https://bit.ly/3vql5Z3)
    5. // return back to cmder and do it to config
        ssh -T git@github.com
```

### To Push New Folder

```sql
    1. git init
    2. git add README.MD
    3. git commit -m "your first commit massage"
    4. git branch -M 'like' master / main
    5. goto github and make repo
    6. git remote add origin 'link repo ssh'
    7. git push -u origin main/master
```

### To push to existing Repo

```sql
    1. goto github and make repo
    2. git remote add origin 'link repo ssh'
    3. git branch -M 'like' master / main
    4. git push -u origin main/master
```

### To push last change

```sql
    1. git status
    2. git add .
    3. git commit -m ""
    4. git push -u origin main/master
```
