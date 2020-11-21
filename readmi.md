# 第一部分
# 第一步 #
初始化  
git init  
# 第二步 #
查看状态   
git status  
# 第三步 #
管理 git add  
git add 文件名  
管理一个文件  
git add .  
管理所有文件
# 第四步
生成颁布  
git commit -m '描述'
# 第五步
查看版本  
git log 

# ps 首次使用git
需要配置个人信息，邮箱  
 git config --global user.name  
 git config --global user.email  


# 第二部分
# 回滚
回滚到以前版本
git reset --hard 版本号

# 查看所有版本（包括已回滚的版本）
git reflog 


