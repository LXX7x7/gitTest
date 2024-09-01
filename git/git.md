```bash
#添加到缓存区
git add <file-name>
#添加所有文件到缓存区
git add .
#取消添加到缓存区
git reset HEAD <file-name>
```

文件的四个状态：

新建文件都是未跟踪状态，通过git add 添加到缓存区

通过git commit 提交文件，形成新的版本

查看文件状态：

```bash
git status
```

查看文件修改内容：

```bash
git diff
```

查看提交记录：

```bash
git log
#以一行展示
git log--pretty oneline
```

 ![1725021196477](image/git/1725021196477.png)

```bash
#提交
git commit -m "备注"
#撤销提交,无法撤销第一次提交
git reset head~ --soft
```


链接远程仓库：

```bash
git remote add <name> <链接>
```

给远程仓库重命名：

```bash
git remote rename <oldname> <newname>
```

推送到远程仓库：

```bash
git push <name> <branch_name>
```
