# 使用git
* 基本操作
* 代码拉取与提交
* 分支操作
* 辅助功能
## 基本操作
> 在某文件夹中右键 Git Bash

>初始化 把它变成仓库
```
git init
```

>查看仓库状态
```
git status
```

>连接git 在创建一个git库之后  地址是在git新建的库上
```
git remote add origin 地址  
```

>在创建文本以后 把文本放入仓库中
```
git add index.html
```

>把所有文件都放入仓库中
```
git add .
```

>放到仓库货架子上
```
git commit -m 'first commit'
```

## 代码拉取与提交
>把本地代码提交到线上 首次提交
``` 
git push -u origin master
```

>把本地代码提交到线上 再次提交
``` 
git push 
```

>把线上代码拉取到本地
``` 
git pull
```

## 分支操作
>查看当前分支
```
git branch
```

>创建test分支
```
git branch test
```

>定位到test分支
```
git checkout test
```

>合并操作  在github上也可以操作
```
git merge test
```

>删除分支线下
```
git branch -d test
```

>删除分支线上
```
git push origin --delete test
```

## 辅助功能
>回退到上一版本
```
git reset --hard HEAD^
```

>回退到上上版本
```
git reset --hard HEAD^^
```

>回退到上100个版本
```
git reset --hard HEAD~100
```

>回退到某版本
```
git reset --hard 具体版本号
```

>撤销 回到上一状态
```
git checkout --fileName
```

>该命令记录每一次命令
```
git reflog
```

我的 github [链接](https://github.com/CDownPace)
