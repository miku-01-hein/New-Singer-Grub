# 少女乐队 Grub主题
 原仓库已有主题:
  - Ave Mujica
  - Mygo!!!
  - Vocaloid
 现新分支已有主题:
  - Mu-F1
  - Mu-F2
  - MUJICA-F1
  - MuJICA-F2
  - MYGO
  - Tianyi
  - VOCALOID-MIKU
  - Xiangzi

# 新加入的内容介绍
  - 额外给 `MUJICA` 新添加了一个新的主题, 额外添加了 `洛天依`、`丰川祥子`、`若叶睦`的主题, 并给若叶睦额外一个主题。

MUJICA-F1
![Preview](https://github.com/miku-01-hein/New-Singer-Grub/blob/main/MUJICA-F1/background.png)
MUJICA-F2
![Preview](https://github.com/miku-01-hein/New-Singer-Grub/blob/main/MUJICA-F2/background.png)
Mu-F1
![Preview](https://github.com/miku-01-hein/New-Singer-Grub/blob/main/Mu-F1/background.png)
Mu-F2
![Preview](https://github.com/miku-01-hein/New-Singer-Grub/blob/main/Mu-F2/background.png)
MYGO
![Preview](https://github.com/miku-01-hein/New-Singer-Grub/blob/main/MYGO/background.png)
Tianyi
![Preview](https://github.com/miku-01-hein/New-Singer-Grub/blob/main/Tianyi/background.png)
VOCALOID-MIKU
![Preview](https://github.com/miku-01-hein/New-Singer-Grub/blob/main/VOCALOID-MIKU/background.png)
Xiangzi
![Preview](https://github.com/miku-01-hein/New-Singer-Grub/blob/main/Xiangzi/background.png)
# 安装教程
 将你选择喜欢的目前已有的其中任意主题如 `$HOME/Public/Singer-GRUB/AVE-MUJICA/Theme/` 那么请在 `/usr/share/grub/themes` 下 `sudo mkdir -p` 这个命令参数创建 `AVE-MUJICA` 目录
 
 `cd` 命令切换至已创建的目录下 `cd /usr/share/grub/themes/AVE-MUJICA`
 再用 `cp` 命令复制过来 `sudo cp -r $HOME/Public/Singer-GRUB/AVE-MUJICA/Theme/* .`
 
  再使用 `vim` 命令编辑 `/etc/default/grub` 配置文件 在下面的 `GRUB_THEME` 那行填写为 `GRUB_THEME="/usr/share/grub/themes/AVE-MUJICA/theme.txt"`
  
  最后再 `sudo grub-mkconfig -o /boot/grub/grub.cfg` 即可 
  
  之后重启就能看见配置好的grub主题啦!
