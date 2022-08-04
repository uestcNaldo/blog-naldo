---
title: "First Writing"
# date: 2022-07-13T00:36:46+08:00
draft: false
slug: first-w
tags: [example, Markdown语法]
categories: [markdown, hugo]
author: Naldo
lastmod: 2022-08-04T22:36:46+08:00
showToc: true
# 主题特色
cover:
  image: "images/moutain.jpg"
  alt: "moutain"
---

# 初次搭建Hugo博客系统

> Hugo is a static site generator.

## Hugo静态站点生成器
---

这是一段段落文字

#### 无序列表

- markdown syntax
- ping
- node

#### 有序列表
1. first
2. second
3. third

#### 代码块
```javascript
// comment
const a = 1;

function test () {

}
```
#### 样式
- 代码 `markdown`
- 加粗 `**markdown**` **markdown**
- 斜体 `*ping*` *ping*
- 加粗和斜体 `***Hugo***` ___Hugo___

#### 链接

超链接语法: `[显示名称](地址 "超链接title")`  
示例: [Markdown语法](https://markdown.com.cn "markdown.com.cn")

尖括号表示法: `<https://markdown.com.cn>`  
示例: <https://markdown.com.cn>

#### 图片

图片Markdown语法: `![图片alt](图片链接 "图片title")`  
  - 水母:
  ![水母](images/jellyfish.jpg)
  - 猫咪:
  ![猫咪](images/cat1.avif)

#### 表格

| Syntax    | Description |   Test Text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here’s this |
| Paragraph |    Text     |    And more |

#### 任务
- [ ] Learn Hugo ❤️
- [x] Learn Markdown语法 😸
- [x] Commit Code 👻
- [ ] Push commit to Github 🔥
- [x] Deploy Website 🧑‍💻

#### Diagrams

##### GoAT Diagrams
> GoAT: Go ASCII Tool
```goat
      .               .                .               .--- 1          .-- 1     / 1
     / \              |                |           .---+            .-+         +
    /   \         .---+---.         .--+--.        |   '--- 2      |   '-- 2   / \ 2
   +     +        |       |        |       |    ---+            ---+          +
  / \   / \     .-+-.   .-+-.     .+.     .+.      |   .--- 3      |   .-- 3   \ / 3
 /   \ /   \    |   |   |   |    |   |   |   |     '---+            '-+         +
 1   2 3   4    1   2   3   4    1   2   3   4         '--- 4          '-- 4     \ 4
```