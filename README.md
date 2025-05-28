# LearnGitHub
学习GitHub的一些资源

cd E:\Study\Git\LearnGitHub\LearnGitHub

git clone https://github.com/XiaoShu2020ace/LearnPython.git 下载到本地

git branch : 查看当前本地分支

git branch <branch-name> ：本地缓存创建新分支；
git checkout <branch-name> 切换分支

git checkout -b <branch-name> 创建并切换分支
git push -u origin <branch-name> 推送到github库

git branch -d <branch-name> 删除本地分支
git push origin --delete <branch-name> 删除github库分支

 git status 查看库内文件状态

本地修改文件后，需要先添加修改

git add . 添加所有文件，或者把.换成具体名称也可以
git commit -m 'Test' 提交缓存，并编写提交日志
git push -u origin main 提交到github库
git pull 拉取库内容，如有冲突解决后注意提交；
git log 显示日志


