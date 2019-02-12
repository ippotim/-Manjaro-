# 安装Manjaro后要做的事 一切之前
* pacman-mirrors -c China
* pacman -Syu
# 安装Manjaro后要做的事 Deepin版
* pacman -Rsn evolution
* pacman -S vim fcitx fcitx-cloudpinyin fcitx-configtool fcitx-qt5 fcitx-gtk3 emacs texstudio texlive-langchinese texlive-latexextra racket ccache cmake gdb valgrind tk qtcreator qt5-examples qt5-charts qt5-3d qemu nasm xorriso mtools wireshark-gtk nodejs thunderbird
# 安装Manjaro后要做的事 Xfce版
* pacman -Rsn audacious ms-office-online steam-manjaro
* pacman -S vim fcitx fcitx-cloudpinyin fcitx-configtool fcitx-qt5 fcitx-gtk3 emacs tmux texstudio texlive-langchinese texlive-latexextra racket ccache cmake gdb valgrind tk gradle virtualbox virtualbox-guest-iso qtcreator qt5-examples qt5-charts qt5-3d qemu nasm xorriso mtools gnome-system-monitor geany wireshark-gtk nodejs
* 可选：pacman -S openjdk8-src noto-fonts-emoji
# 安装Manjaro后要做的事 KDE版
* pacman -Rsn ms-office-online steam-manjaro
* pacman -S vim fcitx fcitx-cloudpinyin fcitx-configtool fcitx-qt5 fcitx-gtk3 emacs tmux texstudio texlive-langchinese texlive-latexextra racket ccache cmake gdb valgrind tk gradle virtualbox virtualbox-guest-iso qtcreator qt5-examples qt5-charts qt5-3d qemu nasm xorriso mtools jdk-openjdk wireshark-qt
# 安装Manjaro后要做的事 一切之后
* gpasswd -a ippotim wireshark
* cp .xprofile .vimrc ~ 将.xprofile .vimrc复制到home目录下
* Qt Creator格式化代码快捷键置为Alt+I
