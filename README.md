# dotfiles

https://www.youtube.com/watch?v=SXdIGNsz2G0

sudo apt-get install vim
sudo apt-get install zsh

Install oh-my-zsh
sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

vim ~/.zshrc

plugins=(git, autoenv, docker, celery, tmux, vi-mode)

git clone https://github.com/stp8954/dotfiles.git
chmod +x .make.sh
.make.sh

sudo apt-get install tmux

git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

vim ~/.vimrc
:PluginInstall


sudo add-apt-repository ppa:ubuntu-desktop/ubuntu-make
sudo apt update 
sudo apt-get install ubuntu-make
testing author

git clone https://github.com/sigurdga/gnome-terminal-colors-solarized.git
cd fnome-terminal-colors-solarized.git
chmod +x set_dark.sh
./set_dark.sh

https://github.com/bhilburn/powerlevel9k
