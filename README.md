# dotfiles
Dotfiles (and related).

Installation instructions (On Ubuntu 14.04):

1) Execute: cd ~  
2) Clone this repository: git clone https://github.com/mauriciogardini/dotfiles.git  
3) Execute: ln -s dotfiles/vim .vim  
4) Execute: ln -s dotfiles/vim/vimrc .vimrc  
5) Execute (If necessary): mkdir .vim/bundle
6) Execute: git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim  
7) Open vim and run: :BundleInstall  
8) If you want Powerline to show the proper symbols:  
  8.1) Execute (If necessary): mkdir .fonts  
  8.2) Execute: cp dotfiles/vim/fonts/Inconsolata-dz-Powerline.otf .fonts/  
  8.3) Execute: fc-cache -fvr  
  8.4) Logout and log in.  
  8.5) Open a Terminal window and set the font to "Inconsolata-dz for Powerline Medium".  
