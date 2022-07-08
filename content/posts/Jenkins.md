---
title: "Jenkins"
date: 2022-07-08T14:14:30+08:00
draft: true
---

# Jenkins
## 下载
[jenkins官网](https://www.jenkins.io/)
## 启动
`nohup java -jar jenkins.jar &`
### 查看启动日志
`tail -f nohup.out`
### 记录admin密码
`This may also be found at: /root/.jenkins/secrets/initialAdminPassword`
`47171b57b4e94e78a5781e7a904e09ee`
## 访问
`IP:8080`  输入记录的admin密码，选择推荐插件
## 自动化构建
### vue
#### 下载相关插件
gitee、nodejs
#### 配置全局环境
nodejs
#### 新建任务
输入名称，选择构建一个自由风格的软件
## 可能问题

- 该Jenkins实例似乎已离线  添加hosts `127.0.0.1 www.google.com`



