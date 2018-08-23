# Dotfiles

My dotfiles (zsh + tmux 2.6 + vim 8 or nvim)

![](./sample/terminal.png)

## How-to-install (for Windows)

1. Get Nerd fonts from <https://github.com/ryanoasis/nerd-fonts>
2. Install Python 3.5 [download](https://www.python.org/ftp/python/3.5.4/python-3.5.4-amd64.exe)

> - Python version should be 3.5 (predefined by window kaoriya vim)
> - DO NOT FORGET TO CHECK `Add Python 3.5 to PATH`

3. Install Git [download](https://github.com/git-for-windows/git/releases/latest)
4. Run command prompt with administrator authorization & execute following commands

```
pip install neovim jedi flake8 pycodestyle autopep8
```

5. Copy `_vimrc` & `_gvimrc` & `vimfiles` to `$HOME` (default `$HOME` is `C:\Users\<user_name>`)
6. Download kaoriya-Vim [download](http://vim-jp.org/redirects/koron/vim-kaoriya/latest/win64/)
7. Copy `$HOME\AppData\Local\programs\Python\Python35\{python35.dll,vcruntime140.dll}` to downloaded `vim*-kaoriya-win64/`

> *.dll should be located in the same directory as gvim.exe

8. Run `gvim.exe`

> Require time for the first time to install plugins

## References

- nerd font: [ryanoasis/nerd-fonts](https://github.com/ryanoasis/nerd-fonts)
