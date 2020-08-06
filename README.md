# dotVim

vim 8 package

## install

> git clone git@github.com:BruceMaa/dotVim.git ~/.vim

## vim-scripts

1. vim-go

```shell
git remote add vim-go git@github.com:fatih/vim-go.git

git subtree add --prefix=pack/plugins/start/vim-go vim-go master --squash
```

2. vim-rust

```shell
git remote add rust.vim git@github.com:rust-lang/rust.vim.git

git subtree add --prefix=pack/plugins/start/rust.vim rust.vim master --squash
```

3. emmet-vim

```shell
git remote add emmet-vim git@github.com:mattn/emmet-vim.git

git subtree add --prefix=pack/plugins/start/emmet-vim emmet-vim master --squash
```

4. molokai

```shell
git remote add molokai git@github.com:tomasr/molokai.git

git subtree add --prefix=pack/plugins/start/molokai molokai master --squash
```

5. nerdtree

```shell
git remote add nerdtree git@github.com:scrooloose/nerdtree.git

git subtree add --prefix=pack/plugins/start/nerdtree nerdtree master --squash
```

6. nerdtree-git-plugin

```shell
git remote add nerdtree-git-plugin git@github.com:Xuyuanp/nerdtree-git-plugin.git

git subtree add --prefix=pack/plugins/start/nerdtree-git-plugin nerdtree-git-plugin master --squash
```

7. vim-airline

```
git remote add vim-airline git@github.com:vim-airline/vim-airline.git

git subtree add --prefix=pack/plugins/start/vim-airline vim-airline master --squash
```

8. vim-airline-themes

```shell
git remote add vim-airline-themes git@github.com:vim-airline/vim-airline-themes.git

git subtree add --prefix=pack/plugins/start/vim-airline-themes vim-airline-themes master --squash
```

9. vim-colors-solarized

```shell
git remote add vim-colors-solarized git@github.com:altercation/vim-colors-solarized.git

git subtree add --prefix=pack/plugins/start/vim-colors-solarized vim-colors-solarized master --squash
```

10. vim-fugitive

```shell
git remote add vim-fugitive git@github.com:tpope/vim-fugitive.git

git subtree add --prefix=pack/plugins/start/vim-fugitive vim-fugitive master --squash
```
