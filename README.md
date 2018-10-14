# sublime-config
这是我的sublime txt 3编辑器的配置文件

## 用法

1. 安装好git、sublime text 3 以及sublime 的package controll (重要)

2. 使用命令转到 sublime text3的packages目录，你会发现有个User目录
  (windows: `『你的安装目录』\Sublime Text Build 3114 x64\Data\Packages`) 

  > 注：如果你是程序安装版的sublime，packages的目录位置是：安装盘C：Users/用户名/AppData/Roaming/Sublime Text 3/Packages/

3. 使用命令 `git clone https://github.com/bert1100/sublime-config.git`，不要使用 `git@github.com:bert1100/sublime-config.git`因为这需要权限的。

4. `rm -rf  User` 删除User目录

5. `mv sublime-config User` 重新命名sublime-config目录为User





## git bash命令

- `cd Packages` 切换到Packages目录
- `ls` 列举当前目录下的所有文件/目录
- `rm -rf  User` 删除User目录或者其他文件
- `mv sublime-config User` 重新命名



### 推荐的一些sublime插件

##### 必须安装的

- "ConvertToUTF8"：一些古老的文件是gb2312的，会遇到乱码，这个插件可以轻松搞定。注意看下作者的readme.md 说明文档，有钱的记得捐赠作者一下。
- "DocBlockr":  写js、php、typescript的注释神器，快速生成代码注释。
- "IMESupport", 这个一定要安装！！ 因为在win 10下 ，第三方输入法（谷歌拼音、搜狗拼音）可能在sublime中定位有问题。
- "Package Control", 这个必须的！快速安装package用的！！！

##### 其他

其他的看情况安装一些，图标呀、语法解析、自动格式化、主体什么的

