# 安装Manjaro后要做的事 一切之前
* pacman-mirrors -c China
* pacman -Syu
* pacman -S vim fcitx fcitx-cloudpinyin fcitx-configtool fcitx-qt5 fcitx-gtk3 emacs texstudio texlive-langchinese texlive-latexextra racket ccache cmake gdb valgrind tk qtcreator qt5-examples qt5-charts qt5-3d qemu nasm xorriso mtools nodejs cppcheck
# 安装Manjaro后要做的事 Deepin版
* pacman -Rsn evolution gedit
* pacman -S thunderbird wireshark-qt geany jdk8-openjdk openjdk8-src gradle
# 安装Manjaro后要做的事 Xfce版
* pacman -Rsn audacious ms-office-online steam-manjaro
* pacman -S tmux gnome-system-monitor geany wireshark-gtk
* 可选：pacman -S openjdk8-src gradle virtualbox virtualbox-guest-iso noto-fonts-emoji
# 安装Manjaro后要做的事 KDE版
* pacman -Rsn ms-office-online steam-manjaro
* pacman -S jdk-openjdk wireshark-qt
# 安装Manjaro后要做的事 一切之后
* gpasswd -a ippotim wireshark
* cp .xprofile .vimrc ~ 将.xprofile .vimrc复制到home目录下
* Qt Creator格式化代码快捷键置为Alt+I
* 如果时间不对，就timedatectl set-ntp true
