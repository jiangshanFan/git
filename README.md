# git
learnig git &amp; apply git

<<<<<<< HEAD
# branch master
Now,master change something about the some ref of README.md ,
git add README.md , git commit -m "on master M README.md", git push origin master.
=======
# branch dev
-git checkout -b dev
-M README.md
-git add README.md
-git commit -m "M README.md"
-git push -u origin dev
<<<<<<< HEAD
>>>>>>> dev
=======

<<<<<<< HEAD
## 本人修改了README.md，并提交推送push远程，发现冲突，
需要先 git pull 拉取，然后合并，解决冲突，在推送
=======
##新的小伙伴创建了一个本地库，并创建分支dev关联origin/dev，就可以在dev上继续修改，时不时push到远程
>>>>>>> 1cdd34fa2b12e803772160c5ea84a78cad94b211
>>>>>>> dev
