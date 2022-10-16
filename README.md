# shell-env
Compact shell env from https://github.com/rightson/shell-dev-env



## Vim
```shell=
$ curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
$ vim -E -s -u "~/.vimrc" +PlugInstall +qall
```



## fzf
```shell=
$ git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
$ ~/.fzf/install --all
```