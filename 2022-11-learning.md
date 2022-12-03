# 闻之





# 见之

* Git
* 侯捷面向对象
* vim编辑
* cJSON源码
* 爬虫
* opencv



# 知之

## Git

1. 安装git 配置到全局 

2. ~~~
   git init      // 初始化仓库
   git add .        // 添加当前所有改动到暂存区
   git commit -m "commit info"     // 从暂存区提交到本地仓库
   git push       // 推送到远程仓库
   
   // ~/下生成.ssh文件，进去打开id_rsa.pub，复制key黏贴到github上
   ssh-keygen -t rsa -C "18379694345@163.com"
   // 连接远程仓库 origin成了远程仓库别名
   git remote add origin git@github.com:little8fish/Plan-A.git  
   git remote -v   // 查看远程分支
   git push -u origin master  // 将master分支推送到远程仓库
   git clone url   // 可以将仓库clone到本地
   // 如果现在在master分支下
   git merge dev  // 将dev分之合并到当前分支，可能需要处理冲突，即两份修改保留一处
   git checkout dev // 切换到dev分之
   git checkout -b branchname  // 创建branchname分支并切换过去
   git branch   // 查看分支
   git branch branchname // 创建branchname分支
   git branch -d branchname // 删除branchname分支
   git ls-files  // 查看
   git commit -am "commit info"   // 直接提交所有更改
   git status   // 查看上次提交之后是否有对文件进行再次修改
   git reset .  // 与add相反
   git reset --soft HEAD^   // 撤销上次提交，回退到暂存区
   git reset HEAD^          // 撤销上次提交和add，回到未add前
   git reset --hard HEAD^   // 撤销提交和add，并且删除工作空间代码，回到上一次的commit状态
   
   
   其它暂未使用到
   ~~~

## 侯捷面向对象



# 行之





