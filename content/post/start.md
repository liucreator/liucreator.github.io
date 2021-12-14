---
title: "哈喽，World！"
date: 2021-12-06T23:20:00-07:00
# weight: 1
# aliases: ["/first"]
tags: ["cn", "个人", "建站"]
author: "ledisthebest"
# author: ["Me", "You"] # multiple authors
showToc: false
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "立flag啦~"
canonicalURL: "https://liucreator.github.io/post/start/"
disableHLJS: true # to disable highlightjs
disableShare: true
hideSummary: false
searchHidden: true
ShowReadingTime: false
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
  image: "profile.jpg" # image path/url
  alt: "profile pic" # alt text
  relative: false # when using page bundles set this to true
  hidden: false # only hide on current single page
editPost:
  URL: "https://github.com/liucreator/liucreator.github.io/blob/main/content"
  Text: "改进建议" # edit text
  appendFilePath: true # to append file path to Edit link
---

从前年开始就想着给自己建一个小站的，拖了那么就久，终于开始动工了。

作为一个射手座，最近也不知为什么特别容易纠结，这不像我呀，，
唉，反正这第一篇帖子也不会有什么人看到的，我就在这里瞎叨叨几句吧～ 😶

其实是一直惦记着的。。。

自己出来的的早，人缘也不怎么样，就想着以后如果能碰到志同道合之人，可以让人了解一下我的过去吧。

来说说截止到现在我都做了些什么吧（没干正事），

- 首先呢，我一直在琢磨：我是应该用什么现成的模板呢还是手抠代码呢？  
   现成的是省事，可要想改动也麻烦，而且很多现成的模板里面有太多的 JavaScript 和其它*Bloat*。
   至于说手打嘛，有亿点儿麻烦，而且我五年前学的 HTML/CSS/JavaScript 也都已经忘得差不多了。。。  
   所以我选择了框架。

- 那么我该用哪个框架呢，花了两天时间，做了点研究，我觉得 Hexo, Hugo 和 Jekyll 不戳。
   从我个人的实验来说 Hugo 是最快且轻量的， 而且编译它需要的 Go 语言环境我也已经有了（以前编译[Yay](https://github.com/Jguer/yay)时留下的，不过我已经换成[Paru](https://github.com/Morganamilo/paru)了），所以就是它了！

- 然后我用 Git 创建了仓库，并开始搭建开发环境。我不大喜欢微软（垄断不是件好事），所以也不太想用它的 Github 来托管代码的，
   可是我现在经常会在外面，Github 有个[Codespace](https://github.com/features/codespaces)（云端的 VSCode，上课用过还阔以），所以我就把项目推到了 Github.  
   可我后来看了文档后才发现， 原来它还在Beta，付费并需要收到邀请，而且得创建个组织才行。😕  
   后来才知道Gitlab比那它更早之前已经出了[Gitpod](https://www.gitpod.io/)，一个月50小时的免费时间，而且可以用在任何的Git项目上，平台不限。所以我就开始在Gitpod的Docker里面配置Hugo了。

- 还刚开始吧，实话实说我还不太懂这个框架的原理，鼓捣了几天给弄“滚挂”了，所以就清空了仓库再来一遍。。
看了半天文档和Wiki，现在做了这个，还行吧？

emmm，我困了。还有好多想聊的，以后再说吧~🌹🌹🌹