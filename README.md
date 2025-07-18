# 我的WezTerm配置

**截图一**

![image](https://github.com/user-attachments/assets/36499980-85c7-4b76-b15f-6658c021e53f)


## 前提条件

**1、安装`wezterm`终端**

[WezTerm终端](https://github.com/wezterm/wezterm/releases)

**2、安装`nerdfont`字体**

[Nerd Font](https://www.nerdfonts.com/font-downloads)

然后下载SylBols Nerd Font  和  DejaVuSansm Nerd Font字体
然后将他们放在~/.fonts/ 或 ~/.local/share/fonts/目录下
最后使用fc-cache -fv命令来刷新一下字体


## 使用教程

1、下载或克隆压缩包到本地

2、将压缩包解压

3、将解压后的文件放入：`$HOME/.config/wezterm`目录底下

Windows目录：C:\Users\Fizz\.config\wezterm

Llinux目录：$HOME/.config/wezterm

Macos目录：~/.config/wezterm 

安装完后重启你的wezterm终端
如果报错的话请修改您的launch.lua文件，并将zsh一行改为'bash',
如果您是windows,将他修改为cmd或power shell
## 快捷键

```bash
#快捷键
Ctrl+shift+c    --复制
Ctrl+shift+v    --粘贴
Ctrl+shift+r    --重命名标签栏
Ctrl+alt+[\]    --水平拆分窗格，即左右拆分
Ctrl+alt+[/]    --垂直拆分窗格，即上下拆分
Ctrl+alt+[-]    --关闭当前窗格
Ctrl+alt+z      --最大化/最小化当前窗格
F11             --全屏
Ctrl+alt+[↑]    --向上扩展窗格
Ctrl+alt+[↓]    --向下扩展窗格
Ctrl+alt+[←]    --向左扩展窗格
Ctrl+alt+[→]    --向右扩展窗格
Alt+[↑]         --放大字体
Alt+[↓]         --缩小字体
Alt+r           --重置字体大小
