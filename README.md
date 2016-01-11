这是一个git training的项目
------------------------------------
## 初识git
  * git 是分布式版本控制系统
  * git 和svn 的主要区别：git会在本地保留完整的项目备份，代码的提交不依赖远程仓库，可以在本地进行多次提交后一起push到远程仓库
  * 目前公开可使用的git服务有很多，如github， bitbucket，也可使用开源的方案在本地搭建内部的git服务
## git 安装：
     从 [git 官网](http://git-scm.com/)下载相应的客户端版本，命令行使用请配置环境变量。
## git 使用：
  * clone 项目： git clone https://tomyang@bitbucket.org/bg3_mobile_java/demo.git 
  * 修改代码
  * 查看改动的文件： git status
  * 提交代码
      * git add: 使用git add filename 将要提交的文件加入缓存，此文件夹下所有的改动都提交使用 git add . 
      * git commit: 使用git commit提交代码到本地仓库，例如 git commit -m "更新user功能", 请使用-m 参数提交日志
      * git push： 使用git push命令将本地所有提交上传到远端服务器