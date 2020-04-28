##  ● git add——向暂存区中添加文件 

>  		如果只是用 Git 仓库的工作树创建了文件，那么该文件并不会被记 入 Git 仓库的版本管理对象当中。因此我们用 git status命令查看 README.md 文件时，它会显示在 Untracked files 里。
>
> ​		 要想让文件成为 Git 仓库的管理对象，就需要用 git add命令将其 加入暂存区（Stage 或者 Index）中。暂存区是提交之前的一个临时区域。 

```
 $ git add README.md $ git status 
 # On branch master
 # 
 # Initial commit 
 # 
 # Changes to be committed: 
 # (use "git rm --cached ..." to unstage) # # new file: README.md 
 # 
```

>  将 README.md 文件加入暂存区后，git status命令的显示结 果发生了变化。可以看到，README.md 文件显示在 Changes to be committed 中了。 

