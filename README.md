# Introduction
**If you use [CtrlP][2], use this plugin [amiorin/ctrlp-z][1]**

This vim plugin was extracted from the .vimrc of the author of fasd.

It allows you to change the current directory of vim using fasd and then it open NERDTree window in new working directory.

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

```sh
# .zshrc
# fasd uses a s d f z zz sd sf
eval "$(fasd --init auto)"
alias v="f -e mvim"
alias o='a -e open'
```

## Reference
* [fasd](https://github.com/clvv/fasd)
* [tlib](http://www.vim.org/scripts/script.php?script_id=1863)
* [.vimrc](https://github.com/clvv/dotfiles/blob/master/.vimrc)
* [nerdtree](https://github.com/scrooloose/nerdtree)

[1]: https://github.com/amiorin/ctrlp-z
[2]: https://github.com/kien/ctrlp.vim


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/amiorin/vim-fasd/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

