### git全局设置

> 设置名称、邮箱。提交代码必须配置

```bash
git config --global user.name "oneutf"
git config --global user.email "2035734975@qq.com"
```



### 新建git仓库，推送至远程库

```bash
# 初始化git仓库
git init
# 暂存所有文件，包括未被追踪文件
git add .
# 提交更新
git commit -m "init"
# 添加一个远程仓库
git remote add origin https://gitee.com/oneutf/note-workspace.git
# 将本地库推送至远程库
git push -u origin master
```



### 操作远程库

#### 添加远程仓库