

# 增强sublime的编码美化效果

> 本文参考的原文： [Simple Visual Enhancements for Better Coding in Sublime Text](https://webdesign.tutsplus.com/articles/simple-visual-enhancements-for-better-coding-in-sublime-text--webdesign-18052)



## 字体

### 基本需求

- 易于分辨单词中的每个字母或数字，防止变量\函数名打错（如：“0”、“o”和“O”，“1”、“I”和"l"等）
- 数字部分等高
- 代码中大量出现的符号（如 # % $ * \）与字母混杂在一起不太丑
- 引号易于辨识，两个单引号「''」和一个双引号「"」区别尽量明显
- 有些环境中要求字体等宽，代码需要对齐
- 支持中文显示




### 字体格式的使用 

windows和mac下 不能安装 .otf格式的字体，因为它们不支持 OpenType-CFF2 格式。

windows： OpenType字体(.TTC) 可缩放字体  和 .ttf

mac：是.tif



### 字体美化设置 Fonts and Spacing

Choosing the right font face and spacing is one of the most personal ways to customize your code. Firstly, choose a suitable coding font face, preferably a monospaced font. Here are a few to look into:

- [Source Code Pro](http://blogs.adobe.com/typblography/2012/09/source-code-pro.html) (`推荐最新版`)
- [Consolas](http://www.microsoft.com/typography/fonts/family.aspx?FID=300) `需要收费` `微软字体`
- [Monaco](http://en.wikipedia.org/wiki/Monaco_(typeface)) `MAC系统下常见字体`
- [Inconsolata](http://levien.com/type/myfonts/inconsolata.html)
- [Anonymous Pro](http://www.marksimonson.com/fonts/view/anonymous-pro)

 Once you've chosen a font, make sure it's installed on your - system, add it to your settings, and adjust the size and spacing - with the following options:

``` js
“font_face”: “Inconsolata";
"font_size": 18;
"line_padding_bottom": 1,
"line_padding_top": 1,

```


- Input [自定义字体](http://input.fontbureau.com/) (`这是我找的自定义字体，也可以用`)

  > 另外是我自己找到的自定义字体，仅供参考。




## 其他

- 高亮行开启： "highlight_line": true,
- 已编辑的行高亮开启： "highlight_modified_tabs": true,
- 标签折叠后按钮不隐藏： "fade_fold_buttons": false,
- 自动换行： "word_wrap": true,
- 菜单中文件夹粗体： "bold_folder_labels": true,
- 显示/隐藏左侧菜单：View → Side Bar → Show Open Files
- 左侧菜单对齐显示：只需双击分割线



## 插件以及其他请看以下原文

https://webdesign.tutsplus.com/articles/simple-visual-enhancements-for-better-coding-in-sublime-text--webdesign-18052