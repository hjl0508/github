git is a distributed version control system.
git is a free software distributed under the GPL.
git has a mutable index called stage.
git tracks changes of file.
Creating a new branch is quick and simple.

# test git rebase to merge commit
    - make some local commit
    - run cmd like next
``` shell
git log 
git rebase HEAD~4  #4是说你要合并结果
#或者
git rebase xxxx #xxxx 是要合并所有提交的前面一个提交的id
#修改要合并的commit
```