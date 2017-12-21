

# 增强sublime的编码美化效果

> 有需求的可查看原文： [Simple Visual Enhancements for Better Coding in Sublime Text](https://webdesign.tutsplus.com/articles/simple-visual-enhancements-for-better-coding-in-sublime-text--webdesign-18052)

## 本文翻译/来源 by weijie

## 基本需求

- 易于分辨单词中的每个字母或数字，防止变量\函数名打错（如：“0”、“o”和“O”，“1”、“I”和"l"等）
- 数字部分等高
- 代码中大量出现的符号（如 # % $ * \）与字母混杂在一起不太丑
- 引号易于辨识，两个单引号「''」和一个双引号「"」区别尽量明显
- 有些环境中要求字体等宽，代码需要对齐
- 支持中文显示




## 字体格式的使用

windows和mac下 不能安装 .otf格式的字体，因为它们不支持 OpenType-CFF2 格式。

#### 建议：

windows： OpenType字体(.TTC) 可缩放字体  和 .ttf

mac：是.tif



## 字体美化设置 Fonts and Spacing

Choosing the right font face and spacing is one of the most personal ways to customize your code. Firstly, choose a suitable coding font face, preferably a monospaced font. Here are a few to look into:

- [Source Code Pro](http://blogs.adobe.com/typblography/2012/09/source-code-pro.html)
- [Consolas](http://www.microsoft.com/typography/fonts/family.aspx?FID=300)
- [Monaco](http://en.wikipedia.org/wiki/Monaco_(typeface))
- [Inconsolata](http://levien.com/type/myfonts/inconsolata.html)
- [Anonymous Pro](http://www.marksimonson.com/fonts/view/anonymous-pro)

 Once you've chosen a font, make sure it's installed on your - system, add it to your settings, and adjust the size and spacing - with the following options:

``` js
“font_face”: “Inconsolata";
"font_size": 18;
"line_padding_bottom": 1,
"line_padding_top": 1,

```


- Input [自定义字体](http://input.fontbureau.com/)

  > 另外是我自己找到的自定义字体，仅供参考。



