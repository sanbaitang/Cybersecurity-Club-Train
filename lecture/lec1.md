

<div style="text-align: center;">
<img src=".\assert\lec1\title.png" width="90%" style="margin: 0 auto;">
</div>


## 本次课程需要掌握的内容

**熟练掌握：**

1. 掌握markdown的基本语法，能够将所学内容以md文档形式展现出来
2. 养成记笔记的习惯：选择自己喜欢的软件在本地记笔记，或者将笔记整理到线上知识库中。

**稍作了解：**

1. 使用`hexo`在本地创建个人博客网站。

   > 如果要让互联网上的其他人访问这个网站，以下两种方法任选其一：
   >
   > - 使用网站托管网站，如github page和gitee page  (lec3会详细说明)
   > - 自己购买服务器和域名 这不在本课教学程范围内





## 本次课程分为以下的四个部分

1. 相比于word，markdown的优点是什么

2. markdown是什么

3. markdown的基本语法

4. 介绍可以使用markdown的工具





# 第一部分：markdown是什么

## 什么是markdown

**总体来说，markdown是一种标记语言。只是因为其语法简单，所以我们常常使用它来编写文档**

- markdown是简化的HTML语言
- markdown语法可以简易地实现：**加粗**，*斜体*，插入代码，数学公式等功能。这些功能可以让文章更容易阅读

>使用HTML表示一级标签： `<h1>这是一级标签</h1>`
>
>使用markdown语法表示一级标签：`#这是一级标签`

- markdown决定了解析的文字是什么，而不会影响样式。

  视觉上的样式应该由css决定

<!--v-->

## 可以用markdown做什么

前面说了，可以使用markdown做笔记，那么具体的使用环境是？

- 在一些博客网站(CSDN,博客园)中编写文章，这些网站通常支持markdown语法。个人认为，编写个人博客对程序员的成长很有帮助。
- **定期以将所学知识整理为文档**  我们在可以本地或者线上定期整理自己所学知识，可以用到markdown
- 为你创建的知识库仓库写wiki,方便其他人的使用 
- 等等等等



# 第二部分：markdown的优点

## 为什么我不喜欢用word编写技术文档

****

> 首先必须说明： **`word`是一个功能强大的富文本编辑器**  如果注重文档完成后的排版工作，那么也可以排版出优美的文档。

我个人不使用word的原因主要有以下两点：

1.  使用markdown时，我可以专注于**文章的文字**，而不用花很多时间在排版的格式上。
2. 写技术博客时，通常需要在文章中插入代码，而使用word表示代码的体验很差。





**如果你实在是用不惯markdown编译器，那么可以尝试其他富文本编辑器**

- [石墨文档官网-在线协同办公系统平台,支持云端多人在线协作文档,表格,幻灯片 (shimo.im)](https://shimo.im/)



## markdown的优势在哪

1. 移植性好： 在本地写好md文档后，我可以直接将其复制粘贴到各种知识库中。

   > 由于markdown诞生时候的语法过于简单，所以各个软件，甚至编译器实现方式不尽相同。所以可能会出现：本地文档中的换行语法在github上不能正常显示等问题。不过这是可以调整的。

2. 语法简单：写文章的时候，需要用到的标签数量为十个左右。只要你有编写博客的习惯，这些语法很快就会变成你的肌肉记忆。

3. 使用范围广，简单易学，环境好配。



<!--v-->

<div class="middle center">
<div style="width: 100%">

# 第三部分：markdown的语法



## 有关markdown的文档

**学习markdown的最好方法就是开始创作文章，最忌讳的就是只是看看，不真正自己动手写文章。** ~~只要写得多了，自然就会记住~~

当你忘记语法时可以现查文档

- [Markdown 基本语法 | Markdown 官方教程](https://markdown.com.cn/basic-syntax/)

- CommonMark的文档：[spec.commonmark.org](https://spec.commonmark.org/0.30/)

  

**其他软件的文档：**

- GitHub GFM 规范： [github.github.com/gfm](https://github.github.com/gfm/)
- Typora 规范：[support.typora.io](https://support.typora.io/Markdown-Reference/)




#  第四部分：可以使用markdown的工具



## 使用markdown的工具

**专门用于做笔记的软件：**

- `MarkText`  开源的markdown编辑器。 github仓库：[marktext/marktext: 📝A simple and elegant markdown editor, available for Linux, macOS and Windows. (github.com)](https://github.com/marktext/marktext)
- `obsidian` 我正在使用的markdown编辑器 官网：[Obsidian - Sharpen your thinking](https://obsidian.md/)
- `typora` 不开源的付费markdown编辑器。 我个人不推荐，因为没有分屏预览
- `语雀` 免费的笔记软件，如果做的笔记想要让别人访问，需要开通会员

**代码编辑器，同时也可以用markdown语法做笔记**

- `vscode + Markdown Preview Enhanced插件` 官方文档：[简介 (shd101wyy.github.io)](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/) ~~功能非常强大，但我个人不习惯用vscode记笔记~~

- `sublime Text 3  + markdown插件` 知乎上其他人写的入门文章：[快速上手Subline Text的几个Markdown插件 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/649764489)
