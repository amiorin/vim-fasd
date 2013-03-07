# Introduction
This vim plugin was extracted from the .vimrc of the author of fasd
It allows you to change the current directory of vim using fasd.

## Usage
```vim
:Z           " interactive directory selection
:Z dir1 dir2 " cd, same functionality as j in autojump
```

## Install
```vim
" .vimrc
Bundle 'tomtom/tlib_vim'
Bundle 'amiorin/vim-fasd'
Bundle 'scrooloose/nerdtree'
```

```sh
# shell
brew install fasd
```

## Reference
* [fasd](https://github.com/clvv/fasd)
* [tlib](http://www.vim.org/scripts/script.php?script_id=1863)
* [.vimrc](https://github.com/clvv/dotfiles/blob/master/.vimrc)
* [nerdtree](https://github.com/scrooloose/nerdtree)
