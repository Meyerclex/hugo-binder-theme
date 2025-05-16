---
title: 站点更新日志 Changelog
description:
date: 2021-06-28
slug: changelog
toc: true
---

## 2025/05/14

- 整理了Tag，做了Tag页。
- 改了翻页键。

## 2025/05/12

- 换了个首页样式，重写了about页面（及其layout）:3
- 奶牛猫图片来自：[snailspng](https://www.tumblr.com/snailspng/718136009412509696/i-love-your-blog-so-much-exactly-my-type-of?source=share)（鼠标悬浮逃跑效果很可爱吧，which means “再会”（这么说谁懂。
- 新增了代码代码复制与高亮。

接下来打算做Tag页（finally。

## 2025/04/16

- 增加了移动端目录。
- 增加了[搜索](/search)页面。
- 整理了以往的主题，放进了[小东西博物馆](/collection)。
- 修改了博客背景图（夜间模式像魔女之家！用的背景在copyright部分都标注了）

以及存一下Pagefind的生成索引代码：`npx pagefind --source public --bundle-dir search`。不要每次都去小爱笔记里翻了！

## 2025/04/14

- 恢复了RSS输出，根据[薯饼的文章](https://zhen-shi.github.io/p/hugo-content-protect-tips/)修改了输出摘要部分。
- 在Archive内增加了版权部份的说明（为什么加在这里，因为放在首页太挤了0v0）。
- 修改日夜切换按钮

## 2025/03/19

给自己加了个Sidebar但不知道加了有啥用（喂）。

## 2025/03/18

- 修改首页布局，增加了猫猫图片。修改了Archive页面显示。之前内容也太长了一点！
- 正文字体改为思源黑体（`Noto Sans CJK SC`）。

## 2025/01/23

由于博客被saveweb的聚合页未经问询直接收录，并在要求删掉收录时被对方称为“极端女权”（可见[图片](https://pub-219f59729cc7474d97beb0f99a13e6bd.r2.dev/picture/2025/image.png)），所以关闭了RSS订阅源。

### 具体做法

删除`public`文件夹中的`index.xml`，并在`config.toml`中加入以下内容：

```
[outputs]
home = ["HTML"]
```
