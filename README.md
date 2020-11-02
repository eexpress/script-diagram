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
## vv/vvv/vvvv
> - 终端下混合选择pac/shadowsocks+v2ray的json配置文件。全部文件需放在一个目录。 \*.json, *.pac。
- 执行文件的路径，需要根据安装的情况设置。
- vv是cli版本，vvv是gui版本。会使用颜色或者checkbox表示上一次的状态。
- vvvv是vala版本。

vv -- cli|vvv -- gui
--|--
![vv](vv命令.png)| ![vvv](vvv.png)
[vv下载](https://github.com/eexpress/bin/raw/master/vv)|[vvv下载](https://github.com/eexpress/bin/raw/master/vv-gui-切换代理-new) [vvv.desktop](https://github.com/eexpress/bin/raw/master/vv.desktop)

![vvvv](vvvv.png)
---
## catimg
![Awuuu](catimg的输出.png)

---
## get-story-爬小说
> 爬在线阅读的网站。暂时支持六个网站。

![get-story-爬小说](get-story-爬小说.png)

[脚本下载](https://github.com/eexpress/bin/raw/master/get-story-爬小说.pl)

---
## 全能转换格式
> 参数: ss/vmess字符串/网页明文表格文本，转换成v2ray格式的json文件。
参数: json文件，转换成对应的ss/vmess字符串。并在tty显示二维码。
---------------------------------------
支持ss原版的二维码识别。(需要安装zbarimg)
为了统一使用v2ray，不支持ssr字符串。
-s --screen 可以截屏识别二维码。暂时使用import截图，需要安装ImagMagick。没添加scrot支持。
-c --clip 可以读取剪贴板的多行数据。

![ss-vmess-text-2-v2ray-json](ss-vmess-text-2-v2ray-json.pl.png)
![ss-vmess-text-2-v2ray-json](ss-vmess-text-2-v2ray-json.1.png)

[脚本下载](https://github.com/eexpress/bin/raw/master/ss-vmess-text-2-v2ray-json.pl)

---
## 点阵显示

![dotchar](dotchar.pl.png)

---

## git
![git](git命令.png)

---
