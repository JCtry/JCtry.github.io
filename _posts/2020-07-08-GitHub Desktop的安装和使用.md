---
title: GitHub Desktop的安装和使用
tags: 
   - GitHub
---

- [GitHub桌面版的下载和安装](#github桌面版的下载和安装)
  - [下载](#下载)
  - [安装](#安装)
- [GitHub桌面版的使用](#github桌面版的使用)
  - [登录账号](#登录账号)
  - [克隆仓库到本地](#克隆仓库到本地)
  - [编辑本地文件](#编辑本地文件)
    - [编辑器编辑](#编辑器编辑)
    - [提交版本Commit](#提交版本commit)
    - [同步至云端](#同步至云端)
  - [创建仓库Repositories](#创建仓库repositories)
    - [本地创建](#本地创建)
    - [同步至云端](#同步至云端-1)
    - [如果上一步将仓库设为私人，则打开设置Settings](#如果上一步将仓库设为私人则打开设置settings)

# GitHub桌面版的下载和安装

## 下载

GitHub桌面版官网下载链接[https://desktop.github.com/](https://desktop.github.com/)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708085803638.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)

（官网下载比较慢，我给大家下好了）

蓝奏云链接：[https://jctry.lanzous.com/iKW8ceebfba](https://jctry.lanzous.com/iKW8ceebfba) 密码：jctry

下载好后只有一个应用程序
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708085240442.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)

## 安装
双击运行即可完成安装（安装路径是强制默认的，一般为[C:\Users\Lenovo\AppData\Local\GitHubDesktop](C:\Users\Lenovo\AppData\Local\GitHubDesktop)）

安装好后桌面会出现快捷方式，双击运行即可
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020070808561730.png)


# GitHub桌面版的使用

## 登录账号
（第一次登录会自动弹出登录页面，File---->Options---->Accounts）

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708085848504.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)

## 克隆仓库到本地

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708090226773.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)

会自动显示你云端上所有的仓库Repositories，选择仓库，设置本地存放路径Local path

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708090236592.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)

点击Clone,开始克隆

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708090409830.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
本地存放路径下就有了
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708090441474.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
## 编辑本地文件

### 编辑器编辑

推荐用 Visual Studio Code 或者 Sublime Text 3 打开

（官网下载都较慢，我给大家下好了）

Visual Studio Code-x64-1.46.1安装包蓝奏云链接[https://jctry.lanzous.com/idaeheekakd](https://jctry.lanzous.com/idaeheekakd)密码：jctry

Sublime Text 3-3211-x64安装包蓝奏云链接[https://jctry.lanzous.com/iixf2eekang](https://jctry.lanzous.com/iixf2eekang)密码：jctry
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708090608736.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
可以设置编辑器（点击Options）
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708091118500.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
编辑器打开进行编写（点击Open in Visual Studio Code）

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708091233178.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)

### 提交版本Commit

本地编辑完后，GitHub Desktop上会检测有提示

点击Commit to master，提交当前版本

![在这里插入图片描述](https://img-blog.csdnimg.cn/2020070809141774.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)

### 同步至云端

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708091649465.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)

## 创建仓库Repositories

### 本地创建

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708092345758.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
输入仓库名，设置本地路径，点击Create repository创建
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708092424730.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
本地创建
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708092602412.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708092630941.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)

### 同步至云端
点击 Publish repository
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708092700667.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
可以选择勾选是否将仓库设为私人
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708092738553.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
同步成功，云端上显示仓库
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708092810817.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
### 如果上一步将仓库设为私人，则打开设置Settings

Settings ---> Options ---> Danger Zone

点击 Change visibility
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708092839299.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
选择public（公开）类型，输入 用户名/仓库名

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708093959133.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)
输入密码重新登录后，仓库就设置为公开了
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200708094059744.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0pDdHJ5,size_16,color_FFFFFF,t_70)

