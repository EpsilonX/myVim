# myVim

##Introduction

This is a simple copy of my .vimrc file and .vim directory.

##Install Plugins

In `vim` window, type `:PluginInstall`, *Vundle* will handle the rest of work.

Plugins including:

1. YouCompleteMe
2. NERDTree
3. vim-fugitive
4. YCM-Generator
5. sparkup

##Bonus

In `.vimrc`, I have made some optimization:

1. `:set mouse=a` will enable VIM with scrolling when using *iTerm*
2. `<ctrl><n>` will open/close Nerd tree
2. I'm using the base vimrc of [amix's vimrc](https://github.com/amix/vimrc)


##Tips

For better use of vim:

1. `:set paste` will open paste mode, which will allow to paste code without auto indent
2. `"+yy` / `"+p` will help you copy/paste contents between clipboards and vim
3. `:! cmd` easy way to use command in vim
4. `^`head of line; `$`tail of line

