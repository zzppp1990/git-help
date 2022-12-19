## 1. github帮助  
github help -> search;  
如：搜索ssh配置。  

ssh配置：  
创建ssh key:  
ssh-keygen -t rsa -b 4096 -C "xxxxx@qq.com"  
添加pub key到github->settings  


## 2. git帮助文档  
https://git-scm.com/book/zh/v2/  

## 3. git拉取  
git clone "..."    
获取最新代码到本地：  
git pull(不推荐使用)  

推荐用法：  
查看远程分支：  
git remote show  
抓取远端最新数据到本地：  
git fetch origin  (origin为远端仓库的名称)  
将这些工作合并到当前所在的分支：  
git merge origin/main  

## 4. git push  
git push origin main  

## 5. 分支操作

