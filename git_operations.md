# Git operations

| 将服务器上有改动的代码下载到本地repo                         |                                                              |
| ------------------------------------------------------------ | :----------------------------------------------------------- |
| 在repo目录下git                                              | 右键Git bash here                                            |
| 确认信息，本地初始化                                         | `git config --global user.name "你的名字或昵称"git config --global user.email "你的邮箱"` |
| 通过命令 git init 把这个目录变成git可以管理的仓库            | `git init`                                                   |
| 把文件添加到版本库中                                         | `git add . / git add -A`                                     |
| 把文件提交到github仓库                                       | `git commit -m "xxxx"`                                       |
| 关联到远程库                                                 | `git remote add origin <远程库的网址>`                       |
| 获取远程库代码与本地代码同步并合并（库不为空则必须做）（好像也不是必须搞） | `git pull --rebase origin master`                            |
| 本地库内容推送到远程                                         | `git push origin master`                                     |
| 状态查询命令                                                 | `git status`                                                 |
| 更新后提交                                                   |                                                              |
| 将修改后的代码添加到暂存区                                   | `git add .`                                                  |
| 将修改后的代码提交到gitee仓库，并注释修改了什么内容          | `git commit -m "xxxx"`                                       |
| 本地仓库内容推送到远程                                       | `git push origin master ('main' for blog commit)`            |