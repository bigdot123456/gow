------------------------------------------------------------
Gow - The lightweight alternative to Cygwin
------------------------------------------------------------
** Chinese introduction
Gow（Cygwin替代软件）
Gow（Cygwin替代软件） 评分:     
软件开发工具推荐 ：Gow 　　Gow是一个轻量级的Cygwin替代软件，它能做的事情是给Liunx软件提供一个Windows系统上的运行环境。Gow是Gnu On Windows的缩写，它跟传统的具有相同功能的Cygwin软件比起来的特点是体积小，Cygwin动辄能达到上百兆，而它的体积不到10MB，但里面却集成了Liunxlinux环境下130多种实用工具软件，其中包括： Shell 环境：bash, zsh 压缩工具： gzip, zip, bzip2, compress SSH软件： putty, psftp, pscp, pageant, plink 上传/下载软件：cURL, wget FTP工具： NcFTP 文本编辑器： vim 文字搜索/查看工具:：grep, agrep, less, cat, tail, head 文件系统操作命令： mv, cp, du, ls, pwd, rmdir, whereis 开发工具：make, diff, diff3, sleep, cvs, dos2unix, unix2dos 　　这个软件跟Cygwin比起来还有个特点，安装了它后，当你点击文件夹右键时，会看到右键菜单里多了一个快捷键，点击这个快捷键，你就会在当前文件路径下打开一个命令行窗口（注意：是Windows的命令行窗口，不是Linux的shell窗口），在这个窗口里，你既可以使用DOS命令，也可以使用Liunx命令，比如：你既可以输入“dir”命令来查看目录结构，也可以输入“ls” 命令查看，效果是一样的。(遗憾的是，ls命令好像是不能正常的显示中文)。


**[Download](https://github.com/bmatzelle/gow/releases)** |
[Home Page](http://wiki.github.com/bmatzelle/gow/) |
[FAQ](http://wiki.github.com/bmatzelle/gow/faq)

Author:   Brent R. Matzelle

ABOUT
-----

Gow (Gnu On Windows) is the lightweight alternative to Cygwin. It uses a 
convenient Windows installer that installs about 130 extremely useful 
open source UNIX applications compiled as native win32 binaries. It is 
designed to be as small as possible, about 10 MB, as opposed to Cygwin 
which can run well over 100 MB depending upon options.

Here are a couple quotes from happy Gow users:

> "Gow is one of the few things that makes Windows bearable/usable"

> "I use Gow constantly. It's awesome."

> "I just wanted to let you know that the GOW Suite is simply great - it is 
far lighter than the Cygwin tool, and is extremely useful. "

FEATURES & BENEFITS
-------------------

- Ultra light: Small, light subset (about 10 MB) of very useful UNIX 
  binaries that do not have decent installers.
- Shell window from any directory: Adds a Windows Explorer shell window 
  so that you can right-click on any directory and open a command 
  (cmd.exe) window from that directory.
- Simple install/remove: Easy to install and remove, all files contained 
  in a single directory in a standard C:\Program Files path.
- Included in PATH: All binaries are conveniently installed into the 
  Windows PATH so they are accessible from a command-line window.
- Stable binaries: All commands are kept up to date but also as stable as 
  possible.


OTHER LINKS
---------------------

- [Release Notes](http://wiki.github.com/bmatzelle/gow/change_log)
- [Contributing](https://github.com/bmatzelle/gow/wiki/contributing)
- [Executables list](http://wiki.github.com/bmatzelle/gow/executables_list)
- [Unix command reference](http://www.pixelbeat.org/cmdline.html)

FEEDBACK
--------

Please submit feedback via the 
[Gow issue tracker](http://github.com/bmatzelle/gow/issues)

Thank you for trying Gow!

Copyright (c) 2006 - 2014 Brent R. Matzelle
