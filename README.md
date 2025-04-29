# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

## 安装方法

``` Shell
[ -d ~/.config/nvim.bak ] && rm -rf ~/.config/nvim.bak
[ -d ~/.local/share/nvim.bak ] && rm -rf ~/.local/share/nvim.bak
[ -d ~/.local/state/nvim.bak ] && rm -rf ~/.local/state/nvim.bak
[ -d ~/.cache/nvim.bak ] && rm -rf ~/.cache/nvim.bak

[ -d ~/.config/nvim ] && mv ~/.config/nvim ~/.config/nvim.bak
[ -d ~/.local/share/nvim ] && mv ~/.local/share/nvim ~/.local/share/nvim.bak
[ -d ~/.local/state/nvim ] && mv ~/.local/state/nvim ~/.local/state/nvim.bak
[ -d ~/.cache/nvim ] && mv ~/.cache/nvim ~/.cache/nvim.bak
git clone -o Github git@github.com:lc-nw/nvim-starter.git ~/.config/nvim
rm -rf ~/.config/nvim/.git*
```

## 删除备份文件

``` Shell
[ -d ~/.config/nvim.bak ] && rm -rf ~/.config/nvim.bak
[ -d ~/.local/share/nvim.bak ] && rm -rf ~/.local/share/nvim.bak
[ -d ~/.local/state/nvim.bak ] && rm -rf ~/.local/state/nvim.bak
[ -d ~/.cache/nvim.bak ] && rm -rf ~/.cache/nvim.bak
```

