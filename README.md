# VIM

## Install VIM

```
$ sudo apt install vim
```

## Import [.vimrc](./vim/.vimrc)

```
$ mv <path to downloads>/.vimrc ~/.vimrc
```

## Install plugins

```
git clone https://github.com/fatih/vim-go.git ~/.vim/pack/plugins/start/vim-go
git clone https://github.com/ctrlpvim/ctrlp.vim ~/.vim/pack/plugins/start/ctrlp.vim
git clone https://github.com/AndrewRadev/splitjoin.vim ~/.vim/pack/plugins/start/splitjoin
git clone https://github.com/SirVer/ultisnips ~/.vim/pack/plugins/start/ultisnips
git clone https://github.com/pineapplegiant/spaceduck ~/.vim/pack/plugins/start/spaceduck
```

## Install dist

```
git clone https://github.com/preservim/nerdtree.git ~/.vim/pack/vendor/start/nerdtree
vim -u NONE -c "helptags ~/.vim/pack/vendor/start/nerdtree/doc" -c q

git clone https://github.com/vim-airline/vim-airline ~/.vim/pack/dist/start/vim-airline
vim -u NONE -c "helptags ~/.vim/pack/dist/start/vim-airline/doc" -c q

git clone https://github.com/vim-airline/vim-airline-themes ~/.vim/pack/dist/start/vim-airline-themes
vim -u NONE -c "helptags ~/.vim/pack/dist/start/vim-airline-themes/doc" -c q

git clone https://tpope.io/vim/fugitive.git ~/.vim/pack/tpope/start/vim-fugitive
vim -u NONE -c "helptags fugitive/doc" -c q
```
