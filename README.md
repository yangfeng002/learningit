本项目主要是演示学习git相关的命令和使用方法
1.申请一个github账号
2.创建创建SSH Key,执行命令  ssh-keygen -t rsa -C "youremail@example.com"
3.在github--settings上面添加上sshkey,在Key⽂本框⾥粘贴id_rsa.pub（在users主目录下面）文件的内容
4.在本地创建git仓库，在github上面创建远程仓库，并将两仓库关联
执行如下命令：
   git remote add origin  https://github.com/yangfeng002/learningit.git
5. 推送本地文件到远程
   git push -u origin master  
   
  


