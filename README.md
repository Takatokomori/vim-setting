# vim-setting


1. Install Vim

```
sudo apt update
sudo apt install vim -y
```

2. Create .vimrc
`touch ~/.vimrc`

3. Install Plugin plug-vim

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

- pluginstall
`:source %`
`:PlugInstall`

- remove plugin
  - remove plugin lines from .vimrc
  - save file then `:source %`
  - run `:PlugClean`
  - press y
