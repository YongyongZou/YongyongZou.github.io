---
title: Hexo搭建个人博客
categories: 
	- 工具
	- Hexo
tags: 
	- 博客
excerpt: 摘要

date: 2020-04-05 00:00:00
updated: 2020-04-05 00:00:00
---

### 下载软件

git 

node.js

notepad++

typora

#### 编程语言

git

markdown

yaml

swig

#### 注册网站

GitHub

leadcloud

谷歌注册



### 步骤

1. 安装notepad++: 编辑配置文件

2. 安装Git及配置Git

   1. 安装git bash软件（ls cd）；

   2. 配置用户名和用户邮箱；

      ```bash
      git config --global user.name "你的GitHub用户名"
      git config --global user.email "你的GitHub注册邮箱"
      ```

   3. 生成rsa码；

      git config --global user.email "1261134087@qq.com"

   4. 将密码存入GitHub；

   5. 新建博客仓库： YongyongZou.github.io;

   6. 设置好master主支和source分支，前者存静态网页后者存源代码；

      ```bash
      git clone git@github.com:YongyongZou/YongyongZou.github.io.git
      ```

3. 获取Hexo主题文件和配置文件：

   1. 站点文件：git clone git@github.com:theme-next/theme-next.org.git
   2. 主题文件：git clone git@github.com:theme-next/hexo-theme-next.git

4. 安装hexo软件及其插件；

   1. 安装node.js(与操作系统一致，如64位系统配64位软件);
   2. 打开命令行以管理员身份运行；
   3. 安装hexo: npm install -g hexo-cli ;
   4. 将步骤3的主题放置在YongyongZou.github.io目录内;
   5. 修改站点文件：比如设置title和url
   6. 生成标签等
      1. hexo new page "tags" "categories" "about"

5. 熟悉编程语言；

6. 上传源代码至GitHub

   git add -A

   git commit -m "提交代码"

   git push origin source 



### 引用

1. [引用1](https://huazou.github.io/archives/58a35b09.html)



