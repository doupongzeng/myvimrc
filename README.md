# 自用vim配置

## 安装

1. Linux

    ```bash
    git clone https://github.com/yuexiahu/myvimrc.git ~/.vim

    # neovim
    ln -s ~/.vim ~/.config/nvim

    # vim
    cp ~/.vim/vimrc ~/.vimrc
    ```


2. Windows

    使用powershell管理员权限

    ```powershell
    git clone https://github.com/yuexiahu/myvimrc.git ~\.vim

    # neovim
    New-Item -ItemType SymbolicLink -Path $HOME\AppData\Local\nvim -Target $HOME\.vim

    # vim
    copy ~\.vim\vimrc ~\_vimrc
    ```
