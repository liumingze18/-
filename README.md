根据说明初始化仓库：
git init （初始化仓库）
git add . （将文件夹内内容加入缓存）
git commit -m "first commit" （提交并添加提交注释，"first commit" 为注释内容）
git remote add origin https://xxxxxx （设置远程Git仓库地址，https://xxxxxx为仓库地址）
git push -u origin master （将缓存之内的内容推入Git仓库）