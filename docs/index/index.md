---
title: 介绍
toc: menu
order: 1
nav:
  title: 介绍
  order: 1
---

# 项目介绍

> 本章将会为您展示 Mix-Space 的功能与特性，并介绍来自开源社区的贡献者，希望你能看完。 :)



## 前后端分离

没错， Mix-Space 采用的是前后端分离的形式，那什么是前后端分离呢？

前后端分离，顾名思义，前后端将会遵循某种规范，后端的接口不变，请求方式不变，即前后端数据交换遵循的某种规范。

这对前端开发将会带来极大的方便，不需要与后端在接口问题上扯皮，同时也方便了为 Mix-Space 开发前端的人，这点我稍后再讲。

## 现有功能

- 仪表盘

  可以总览各类数据，一言和今日诗句来自第三方服务。![仪表盘](https://cdn.jsdelivr.net/gh/mx-space/docs-images@latest/images/V0BRMI.png)

- 文章

  可以发布，修改，删除，标记文章。![文章](https://cdn.jsdelivr.net/gh/mx-space/docs-images@latest/images/Vd1kAW.png)

- 日记

  可以发布，修改，删除，标记日记，同时为了方便回忆，兼备定位功能（需要配合高德地图 API）。![日记](https://cdn.jsdelivr.net/gh/mx-space/docs-images@latest/images/mAwG4T.png)

- 编辑器

  现支持`monaco` ， `codemirror` ，`vditor` ， `plain` 这四种编辑器，其中 `vditor` 这个编辑器获得的体验不亚于 `Typora` 。![编辑页](https://cdn.jsdelivr.net/gh/mx-space/docs-images@latest/images/ROaydk.png)

- 评论

  评论有三种类型，没读过的、读过的、被判断为垃圾评论被过滤的。![评论管理](https://cdn.jsdelivr.net/gh/mx-space/docs-images@latest/images/oNhuO0.png)

- 说说

  说说可以用来记录一句话，或者直接保存发布一条[一言](https://hitokoto.cn/)。![说说编辑](https://cdn.jsdelivr.net/gh/mx-space/docs-images@latest/images/gMs43j.png)

- 友链

  在这里可以直接管理友链，新增的未审核的友链会通知到主人，主人通过之后也会邮件通知到对方。![友情链接](https://cdn.jsdelivr.net/gh/mx-space/docs-images@latest/images/server-links.png)

- 数据大盘

  您可以看到今日访问的`PV` 、`UA` ，及近期访问相对频繁的`URL` 。![数据大盘](https://cdn.jsdelivr.net/gh/mx-space/docs-images@latest/images/2ke5KU.png)

- 备份

  在这里可以管理备份，包括下载和直接回滚，或者上传数据文件进行恢复。（需要 mongodb-tools）![备份](https://cdn.jsdelivr.net/gh/mx-space/docs-images@latest/images/cTOSl.png)

- Markdown 导入导出

  该功能可以将所有文章导出为 Markdown YAML 兼容的格式，或者导入 Markdown YAML 兼容的文件。（Hexo 兼容的 Markdown）![导出页](https://cdn.jsdelivr.net/gh/mx-space/docs-images@latest/images/server-md.png)



- ​	搜索功能，基于 Algolia Search，在前端唤出搜索框 `Command` +`K` 或者 `/` 。注意：Windows下为 `Ctrl` + ` K` 或者 `/` 

## 写在目录前

本次主要改变：

- 文档整体结构调整
- 增加模块索引
- 文档逻辑优化

## 目录

| 模块     | 描述                           | 地址                                                     |
| -------- | ------------------------------ | -------------------------------------------------------- |
| 部署     | 整个项目的部署方法             | [起飞](/deploy)                                          |
| 设置     | 项目各部分设置的介绍           | [起飞](/setting)                                         |
| 常见问题 | 部署及使用中未提到的问题，收录于此   | [起飞](/help)                                            |
| 开发     | 介绍项目的开发，请求处理流程等 | [起飞](/dev)                                             |
| 旧版文档 | 旧的文档                       | [走你](https://github.com/mx-space/docs/tree/master/old) |

## 鸣谢

本版文档由以下贡献者编写

- [提莫酱](https://www.timochan.cn)
- [喵二](https://www.miaoer.xyz)
- [623337308](https://blog.cqsjyz.com)
- [Wibus](https://github.com/wibus-wee)
- [zsbai](https://github.com/zsbai) 
- [wuhang2003](https://github.com/wuhang2003)

当然，整个项目的开发者是 [innei](https://innei.ren) 。

感谢社区提出的问题及解决方案、帮助笔者简化许多步骤，也欢迎更多人能够参与到我们的开源社区中[帮助我们优化项目](https://github.com/mx-space)。


## 打赏本项目

- 微信二维码

<div align="center">
<img src="https://cdn.jsdelivr.net/gh/Innei/img-bed@master/20191211132347.png" style="width:40%;" />
</div>
