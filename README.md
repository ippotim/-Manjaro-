# 安装Manjaro后要做的事 一切之前
* pacman-mirrors -c China
* pacman -Syu
* pacman -S vim texstudio texlive-langchinese texlive-latexextra racket ccache cmake gdb valgrind tk qtcreator nodejs cppcheck fcitx fcitx-cloudpinyin fcitx-configtool fcitx-qt6 tmux gnome-system-monitor geany wireshark-qt gradle virtualbox virtualbox-guest-iso noto-fonts-emoji noto-fonts-cjk make viewnior parole qemu nasm xorriso mtools

* pacman -Rsn ttf-dejavu // 就是这个导致Java的Swing里不显示彩色Emoji
* pacman -Rsn audacious

# 安装Manjaro后要做的事 一切之后
* gpasswd -a ippotim wireshark
* cp .xprofile .vimrc ~ 将.xprofile .vimrc复制到home目录下
* Qt Creator格式化代码快捷键置为Alt+I
* 如果时间不对，就timedatectl set-ntp true
