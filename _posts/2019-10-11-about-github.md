---
layout:     post
title:      Git及github的中文简体学习资料
subtitle:   学习资料存档
date:       2020-04-20
author:     loongyowl
header-img: img/post-bg-debug.jpg
catalog: true
tags:
    - 编程
    - 学习
---

学习Github的一些内容和资料存档



# Git及github的中文简体学习资料

[git中文介绍](https://book.git-scm.com/book/zh/v2)

[Github Desktop(windows桌面版)简易教程](https://blog.csdn.net/li_l_il/article/details/90524733) 

[Github Desktop界面翻译](https://www.jianshu.com/p/a6fc842f501d)





学习本文之前首先了解两个概念，Git 和 Github。

**Git是一款免费、开源的分布式版本控制系统**，**简单来说，就是一个管理你的「代码的历史记录」的工具**

**Github是用Git做版本控制的代码托管平台，它提供了web界面，你可以在上面创建资源仓库来存放你的项目。**

本文适合Git新手，帮助你学习Git图形化界面操作，快速上手然后进行工作。

#  

# 1、注册Github账号

**step 1:** [https://github.com 注册地址](https://link.jianshu.com/?t=https://github.com) 输入昵称，邮箱，密码注册



![img](https://upload-images.jianshu.io/upload_images/926678-bb4247ad1cf44f16.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step1: Github 账号注册页面



**step2**: 选择你的私人计划（personal plan），即选择免费用户还是付费用户，免费用户只能创建开源仓库，也就是所有人都可以看你的项目。



![img](https://upload-images.jianshu.io/upload_images/926678-0f6419c5c234d772.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step2: 选择免费用户



**step3:** 登录注册的邮箱，验证账号。

# 2、创建仓库



![img](https://upload-images.jianshu.io/upload_images/926678-c97dcb39c6848472.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step1: 创建仓库



![img](https://upload-images.jianshu.io/upload_images/926678-d7b416666677cf33.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step2: 填写一些资料



![img](https://upload-images.jianshu.io/upload_images/926678-28d144d7c903656e.png?imageMogr2/auto-orient/strip|imageView2/2/w/1145/format/webp)

Step3: Github上的项目页面（图片来源http://blog.csdn.net/android_zyf/article/details/64175941）



# 3、安装GitHub Desktop 

[下载地址：https://desktop.github.com/ ](https://link.jianshu.com/?t=https://desktop.github.com/)选择适合你的版本下载

安装好GitHub Desktop后，第一次运行时需要输入GitHub.com的用户名和密码



![img](https://upload-images.jianshu.io/upload_images/926678-7519cd34ed4d23a2.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

GitHub Desktop 的界面

# 4、创建本地仓库



![img](https://upload-images.jianshu.io/upload_images/926678-367f360295ab4956.png?imageMogr2/auto-orient/strip|imageView2/2/w/820/format/webp)

Step1: new Repository



![img](https://upload-images.jianshu.io/upload_images/926678-e38b2fa0a4bbc69b.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step2: 填写仓库名字、描述，选择存放地址



![img](https://upload-images.jianshu.io/upload_images/926678-bf4e502911325dc2.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step3: 在文件夹打开



![img](https://upload-images.jianshu.io/upload_images/926678-7143743421d6ec43.png?imageMogr2/auto-orient/strip|imageView2/2/w/894/format/webp)

Step4: 添加自己到项目文件



![img](https://upload-images.jianshu.io/upload_images/926678-db6bbbec2487b20a.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step5: 提交改动

# 5、提交改动到远端（Github.com）



![img](https://upload-images.jianshu.io/upload_images/926678-aabfb7e21e9dbe8f.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

推送到本地到仓库到远端

成功之后，就可以在自己到Github 项目页面看到新提交到项目了。通过GitHub Desktop你已经能够把本地的项目文件跟远端（Github.com）上的项目关联起来。



![img](https://upload-images.jianshu.io/upload_images/926678-1788f0b9c341b214.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Github.com 个人项目页

# 6、从远端拉取仓库

除了本地创建仓库推送到远端，我们也可以从远端拉取项目（Clone）



![img](https://upload-images.jianshu.io/upload_images/926678-afe63a1d023f1145.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step1: 进入自己的项目页面，复制项目地址



![img](https://upload-images.jianshu.io/upload_images/926678-47165ae04a6d4a23.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step2 回到Github Desktop



![img](https://upload-images.jianshu.io/upload_images/926678-cf4cbcfe87c3535a.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step3: 粘贴地址，Clone

# 7、本地提交和推送

成功从远端拉取项目之后，你可以使用自己喜欢的编辑器打开，编辑好文件之后，再提交改动到远端



![img](https://upload-images.jianshu.io/upload_images/926678-e3af804b825995df.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step1: 本地提交

此时提交仍然是属于本地的，如果需要提交到远端（Github.com）还需要进一步推送



![img](https://upload-images.jianshu.io/upload_images/926678-47951b12c77a347b.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step2: 点击Push origin 就可以推送到远端

# 8、版本回滚

通过第7步，可以轻松的看到自己对项目的改动，哪怕只是改了一个空格，一个分号，都会有清晰的显示，再也不用害怕不小心改错地方了。

是不是非常的愉快，那如果改完之后又后悔了，有没有后悔药？

答案是，当然有，你可以轻松的回到任何的一次修改。

**情况一**，你还没提交代码，这时候最简单，只需要文件右键"**Discard Changes**" 放弃更改即可



![img](https://upload-images.jianshu.io/upload_images/926678-ed0d179f27c45b25.png?imageMogr2/auto-orient/strip|imageView2/2/w/982/format/webp)

Discard Changes

**情况二**，你已经提交代码，操作也非常简单，右键选择"**Revert This Commit**" 恢复到当前提交



![img](https://upload-images.jianshu.io/upload_images/926678-bec0c894d63f6e6d.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Revert This Commit

# 9、新增分支

创建和切换分支到操作很简单，关于分支到概念 请看 [阮一峰的 Git分支管理策略](https://link.jianshu.com/?t=http://www.ruanyifeng.com/blog/2012/07/git.html)



![img](https://upload-images.jianshu.io/upload_images/926678-7c486a933362c8f8.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

step1: New Branch



![img](https://upload-images.jianshu.io/upload_images/926678-5b90ddf167f77e78.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

step2: 填写分支名字

# 10、合并分支

现在我在dev开发分支上做了添加了login.html，那么如何合并到master分支呢？



![img](https://upload-images.jianshu.io/upload_images/926678-ca6afa183584c2e1.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

dev分支

首先，我们需要切换到Master分支，



![img](https://upload-images.jianshu.io/upload_images/926678-07d81ca0a67d31fc.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step1: 切换分支



![img](https://upload-images.jianshu.io/upload_images/926678-4844a8a7e3767f5d.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step2: 合并到当前分支



![img](https://upload-images.jianshu.io/upload_images/926678-0701257cd06bb4bf.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

Step3：把dev的变化合并到master分支

此时，你会发现master分支上的提交历史已经有了“添加login”这个改动，这说明合并已经成功。

# 11、解决冲突

以上操作，一个人玩的时候溜溜的，很愉快，但实际工作中，经常是多人一起开发，这时候，两个人同时改了同一个地方，就会出现冲突的情况。

比如我在dev分支和master分支对同一个地方进行改动，



![img](https://upload-images.jianshu.io/upload_images/926678-ebf3bd6ac92883a9.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

dev分支



![img](https://upload-images.jianshu.io/upload_images/926678-4aadad0e1fa5106f.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

master分支



![img](https://upload-images.jianshu.io/upload_images/926678-ce50d11cecf9821e.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

在合并分支的时候就会出现冲突

这时候，点击关闭提示，再看 Changes， 冲突的文件已经列出来



![img](https://upload-images.jianshu.io/upload_images/926678-7ba54640825517cf.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

冲突在GitHub Desktop的体现

我们可以在编辑器中修改，



![img](https://upload-images.jianshu.io/upload_images/926678-9963a3f3fa8effee.png?imageMogr2/auto-orient/strip|imageView2/2/w/1120/format/webp)

冲突在编辑器中的体现

必须注意的是，解决完冲突的代码不能有 **<<<<<<< HEAD  =======  >>>>>>> dev** 这些标记



![img](https://upload-images.jianshu.io/upload_images/926678-f2111d4555f383d5.png?imageMogr2/auto-orient/strip|imageView2/2/w/828/format/webp)

解决完冲突的代码



![img](https://upload-images.jianshu.io/upload_images/926678-b1aec44558daac37.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

提交解决冲突后的合并

# 12、Fork 别人的项目

通过前面的步骤，日常的工作已经能轻松进行，但Github除了托管自己的项目，上面也汇集了大量优秀的开源项目，我们如何快速的克隆别人的项目？

以Vux项目为例子：



![img](https://upload-images.jianshu.io/upload_images/926678-0a4bcd90bedd84c9.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

vux 的项目页

Fork之后，我们已经克隆了一个作为自己的项目版本，可以进行任意的开发和学习



![img](https://upload-images.jianshu.io/upload_images/926678-9842b5a63176fb15.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

现在我们也有一个vux项目了

在做了一些创造性开发之后，你可以向原作者提交合并的申请，



![img](https://upload-images.jianshu.io/upload_images/926678-a903588549072850.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

点击New pull request



![img](https://upload-images.jianshu.io/upload_images/926678-1690392c0a1e6292.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

合并的请求

这时候原作者就会收到一个合并请求，他可以通过审核你的提交，来决定需不需要合并。



**小结：**

以上主要是GitHub Desktop的简单使用教程，图形化的界面非常容易上手，很适合Git的新手快速学习和使用。

除了GitHub Desktop其实还有一款Git的客户端也非常好用，小编现在的工作团队也正在使用，操作跟GitHub Desktop大同小异，两者的易用性嘛，仁者见仁。

下面放一张主界面图片预览一下，[SourceTree下载地址](https://link.jianshu.com/?t=https://www.sourcetreeapp.com/)



![img](https://upload-images.jianshu.io/upload_images/926678-3257f3ecc90de0a3.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

SourceTree