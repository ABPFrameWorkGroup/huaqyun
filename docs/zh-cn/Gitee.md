### 码云多人协作流程
>1.先由项目负责人创建仓库。
2.邀请成为仓库管理员。
3.在桌面创建的新文件中打开git Bash
4.git clone 仓库地址
5.git checkout -b 分支名 //创建一个分支
6.开始编辑自己的代码 // 在自己的分支编辑！！！
7.git add . //提交新文件(new)和被修改(modified)文件，不包括被删除(deleted)文件
8.git commit -m ‘描述’ //提交代码到分支
  git branch  （命令查看当前分支）
9.git push origin 分支名 //推送到分支
10.git checkout master //切换到主分支

git pull origin 分支名 //此时在主分支下，拉取分支  打开代码运行查看是否能正常运行，如有错误需要手动修改。
git merge dev 或者合并dev到主分支


12.冲突解决后再 git push origin 主分支
13.打开码云刷新个人主页查看一下有没有推送成功。


git add .
git commit -m ‘修改啦啥’
git push

注意：git branch  （命令查看当前分支）
注意：git checkout xxx  （切换到xxx分支）
注意：然后可以对master分支设置成保护分支，这样就只有管理员可以push上去了，到时候再进行合并，不然多人直接push到master分支容易出错误