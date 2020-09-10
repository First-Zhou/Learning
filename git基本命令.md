#### git基本命令

```bash
# 初始化文件夹为 git 管理文件
git init

# 添加文件
git add <filename>
git commit -m "文件的解释说明"

# 查看版本记录
git log # 查看当前版本及之前版本的记录
git log --pretty=oneline # 显示一行信息
git log --graph --pretty=oneline # 显示版本流程图
git reflog # 查看操作记录

# 版本回退与切换
git reset --hard HEAD^/HEAD~1 # 回退一个版本
get reset --hard "版本编号"

# 暂存修改
git checkout <filename> # 从工作区撤销
git reset HEAD <filename> # 从缓存区撤销

# 删除文件
rm file
git add/rm <filename>
git commit -m "解释说明"

# 分支管理
git branch # 查看分支
git branch <name> # 创建分支
git checkout <name> # 切换分支
git checkout -b <name> # 创建并切换分支
git merge <name> # 快速合并当前分支和 name 分支
git branch -d <name> # 删除分支
```

<img src="\Image.assets\git工作图.PNG" alt="git工作图" style="zoom: 80%;" />
