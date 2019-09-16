# 好用的脚本图解
---
## fd
> - 搜索当前目录文件，相当于简化美化了的find。参数为"与"关系。
- 多彩色，可排除(减号)，支持正则(和bash冲突的符号需要引号包裹)。

![fd](fd命令.png)

[脚本下载](https://github.com/eexpress/bin/raw/master/fd)

## loc

> - 另外一个类似功能的locate版本。
- 定位当前目录文件。参数为"与"关系。

[脚本下载](https://github.com/eexpress/bin/raw/master/loc)

---
## gc
> - 简化强化了的多个关键词grep，参数为"或"关系。
- 多彩色，可排除，支持正则。
- 只工作在管道环境。
- 如果想要全文输出(不过滤)，只彩色标记，可修改脚本里面的`$o=1;`

![gc](gc命令.png)

[脚本下载](https://github.com/eexpress/bin/raw/master/gc)

---
## rename.bash
> - 批量改名文件。支持连续的perl正则操作。
- 带预览和确认。

![rename](rename命令.png)

[脚本下载](https://github.com/eexpress/bin/raw/master/rename.bash)

---
## o
> - 终端下鼠标选择文件，按o回车，快速打开(xdg-open方式)。
- 参数输入也可以残缺。比如`abc-xyz.json`，可以`o xyz.js`打开。
- 依赖xclip命令。

![o](o命令.png)

[脚本下载](https://github.com/eexpress/bin/raw/master/o)

---
## catimg
![Awuuu](catimg的输出.png)

---

## git
![git](git命令.png)

---