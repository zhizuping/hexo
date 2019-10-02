学习制作网页，hexo是第三方，为搭建网址的框架
github是所预览的网页，以及存放hexo的代码，
markdown：http://silencejql.coding.me/Hexo%20Markdown.html
git上传代码：https://www.cnblogs.com/520lqlst/p/8375976.html
git下载代码：git clone ssh
分支关系
再来复习一下创建新仓库的指令：

　　git init //把这个目录变成Git可以管理的仓库
　　git add README.md //文件添加到仓库
　　git add . //不但可以跟单一文件，还可以跟通配符，更可以跟目录。一个点就把当前目录下所有未追踪的文件全部add了 
　　git commit -m "readme" //把文件提交到仓库
　　git remote add origin git@github.com:zhizuping/hexo.git//关联远程仓库
　　git push -u origin master //把本地库的所有内容推送到远程库上
master是远端分支，yujianping_1002是新建的分支，以后push到自己新建的分支。
学习各种编程：参考廖雪峰，菜鸟教程

hexo教程：https://www.cnblogs.com/wsmrzx/p/9439284.html