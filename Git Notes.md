### Git Notes

[toc]

#### Git 常用命令

| 名称名称                             | 作用           |
| ------------------------------------ | -------------- |
| git config --global user.name 用户名 | 设置用户签名   |
| git config --global user.email 邮箱  | 设置用户签名   |
| git init                             | 初始化本地库   |
| git status                           | 查看本地库状态 |
| git add 文件名                       | 添加到暂存区   |
| git commit -m "日志信息" 文件名      | 提交到本地库   |
| git reflog                           | 查看历史记录   |
| git reset --hard 版本号              | 版本穿梭       |

#### git 分支命令

| 命令名称          | 作用     |
| ----------------- | -------- |
| git branch 分支名 | 创建分支 |
| git branch -v|查看分支|
| git checkout 分支名  |  切换分支  |
| git merge 分支名  | 把指定的分支合并到**当前**分支上 |

#### 团队协作

| 命令名称 | 说明 |
|--------------|--------|
| git remote -v | 查看别名信息 |
| git remote add <别名> https://github.com/coco-road/git.git | 给GitHub上的 git 起表名 别名 |
| git **push** <别名> master | 将master分支**推向**远程库 |
| git remote rm <别名> | 移出别名 |
| git remote  set-url  <别名>  [url]  | 修改别名中git的url地址 |
| git **pull** <别名> master | 从远程库拉取 |
