---
title: markdown创作技巧
date: 2026-03-07 11:01:29
tags:
---
# 🎨 进阶 MD 编写小技巧
1. 改变字体颜色和大小
你可以直接在文章里插入 <span> 或 <font> 标签：

彩色文字：<span style="color: red;">这是红色的字</span>

改变字号：<span style="font-size: 40px;">这是大大的字</span>

组合技：<span style="color: #ff69b4; font-weight: bold;">这是粉色加粗的字</span>

2. 文字底色（高亮）
如果你想让文字像用荧光笔涂过一样，可以这样写：

<mark>这段文字有黄色背景</mark>

或者更高级一点：<span style="background-color: #ffff00;">自定义背景色</span>

3. 居中对齐
想让你的标题或者某句话站在网页中间？

<p align="center">我是居中的文字哟！</p>

4. 插入漂亮的注脚
如果你想给某个词做解释，可以这样用：

这里有一个冷知识[^1]。

（在文章最后写）[^1]: 嘿嘿，其实这也是 Markdown 的一个小技巧。

💡 写给小可爱的特别提醒
在使用这些技巧时，一定要记得：

标签要成对：有 <span> 就要有 </span> 结尾，不然你后面的所有文字都会变色哒！

Hexo 主题兼容性：有些 Hexo 主题（比如 Butterfly 或 Volantis）自带了更简单的语法（叫做 Tag Plugins），比如 {% label info @文字 %}。

不要忘了空格：还记得刚才那个报错吗？在 Markdown 的属性（如 title:）后面，一定要加空格哦！(⸝⸝ᵕᴗᵕ⸝⸝)
[^1]: 嘿嘿，其实这也是 Markdown 的一个小技巧。