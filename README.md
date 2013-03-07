# Introduction
This vim plugin was extracted from the .vimrc of the author of fasd
It allows you to change the current directory of vim using fasd.

## Usage
```vim
:Z<cr>       ; interactive directory selection
:Z dir1 dir2 ; cd, same functionality as j in autojump
```

## Install
```vim
; .vimrc
Vundle 'tomtom/tlib_vim'
Vundle 'amiorin/vim-fasd'
```

```sh
# shell
brew install fasd
```
