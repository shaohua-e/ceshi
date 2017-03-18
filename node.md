## 查看
```
ls -al 查看所有文件
```
## 创建文件
```
touch **

cat **  查看文件内容

vi ** 进入编辑状态

编辑后 按esc退出编辑状态,
esc + :wq 保存退出
强制退出 q!
```
## 加到暂存区
```
git add **(需要放的文件名)
git add . (添加所有文件)
或git add -A
```

## 提交到历史区
```
git commit -m "****"
```
## 对比代码
默认是工作区和暂存区
```
git diff

git diff --cached  暂存区和历史区比

git diff master(分支名) 工作区和历史区
```
## git checkout 文件名
```
从暂存区拉回到工作区
```
## 回滚
```
git log 看当前以及之前的日志
git reset --hard 版本号

git reflog 看所有的日志
```

### 分支管理
- 查看分支
```
git branch
```
- 创建分支
```
git branch <branchName>
```
- 切换分支
```
git checkout <branchName>
```
- 删除分支(不能自己删除自己)
```
git branch -D <branchName>
```
- 创建并切换分支(相当于在当前分支的基础上复制一份)
```
git checkout -b <branchName>
```
- 合并代码 (在当前分支上 合并<branchName>,把<branchName>的代码合并到当前分支上)
```
git merge <branchName>
```

## 创建空仓库
- 创建空仓库,写一个仓库名
```
new respository
```
- 本地要建


```
git log --grep=me 搜索备注为me的
git log --author=zhufeng 搜索作者为珠峰提交的
```

- 命令行里创建一个包含内容的文件(>> 表示增加内容, > 会覆盖原来的文件)
```
echo ".idea" >> .gitignore
```

- 连接远程地址
```
git add
git commit -m ""
git remote add origin <url>
git remote -v 查看所有关联
git remote rm <name>

```

- 推到远程地址
```
git push origin master -u (upstream下次提交不必再输入origin master)
git push origin master
```


