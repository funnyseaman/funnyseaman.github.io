---
layout: post
title: 如何快速拥有一个博客
date: 2020-07-14
Author: Sinan Fan
tags:
  - [blog]
comments: true
toc: true
---

可以参考致谢中的两个方案，或者直接 fork [我的仓库](https://github.com/funnyseaman/funnyseaman.github.io){:target='\_blank'}

简单修改 \_config.yml 文件后，就拥有了属于自己的博客了

总之，我们先要有一个自己的站点，才能继续后面的操作

---

## 编辑博客内容

博客.md文件放在 \_posts 文件夹下，所以创建/更新/删除博客，都只需要在对应的.md文件上操作

编辑.md文件有两种方式

1. 直接在 github 仓库上操作，简单易懂
2. 将项目用 git 克隆至本地，使用 [Atom](https://atom.io/){:target='\_blank'} 操作，下面会再介绍

关于博客内的图片，也有两种方法调用

1. 把图片放在 images 文件夹内，调用 GitHub 仓库内资源
2. 把图片放在 [SM.MS](https://sm.ms/){:target='\_blank'} 这类图床上，调用外链

---

## Atom

[Atom](https://atom.io/){:target='\_blank'} 是 github 专门为程序员推出的一个跨平台文本编辑器。具有简洁和直观的图形用户界面，并有很多有趣的特点：支持 CSS，HTML，JavaScript 等网页编程语言。它支持宏，自动完成分屏功能，集成了文件管理器。

##### 下载方法
1. [官网下载](https://atom.io/){:target='\_blank'}
2. [Github下载](https://github.com/atom/atom/releases/tag/v1.48.0){:target='\_blank'}
3. [我的百度链接](https://pan.baidu.com/s/1piWqfpDpJky1mGKmCpF-HA){:target='\_blank'}（提取码：0pdo）

##### 使用方法

![Atom_howToUse](https://i.loli.net/2020/07/14/phHA7UOjCo6RWVI.png)

1. stage
2. commit
3. push

push后，过一会儿博客就会自动更新了

---

## SM.MS

[SM.MS](https://sm.ms/){:target='\_blank'} 是一个免费图床，可以把图片放在 SM.MS 上，通过外链来调用图片。

##### 使用方法

![SM.MS_howToUse](https://i.loli.net/2020/07/14/96U5eKDEY3Vro7t.png)

1. 注册 SM.MS 账号（不注册也可以使用，但是存入的图片不会被归属于用户）
2. 上传图片
3. 获取外链
4. 将外链插入博客中，方法为
``` ![SM.MS_howToUse](https://i.loli.net/2020/07/14/96U5eKDEY3Vro7t.png) ```
