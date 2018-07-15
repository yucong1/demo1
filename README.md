# README

hello git

git 命令学习笔记：  
git init	//初始化一个仓库  
git status 	//查看状态信息  
git log 	//查看提交的日志信息  
git add 文件名	 //将文件添加到暂存区  
git add . 	//直接将所有文件添加到暂存区  
git commit -m “提交的描述信息" 	     //将暂存区的文件提交到本地仓库中  
git commit -a -m "提交的描述信息"    //直接将文件放在暂存区并提交到本地仓库中（add和commit两步二合一）    
git remote add origin https://github.com/yucong1/demo1	  //与远程仓库建立联系并起名字为origin   
git remote -v	//查看与远程仓库建立的连接  
git push origin master	   //将本地仓库master主分支推送到远程仓库   
git pull origin master     //将远程仓库拉到本地master主分支  
git clone https://github.com/yucong1/demo    //将远程仓库clone到本地
