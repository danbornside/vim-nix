# vim-nix

[![Build Status](https://travis-ci.org/LnL7/vim-nix.svg?branch=master)](https://travis-ci.org/LnL7/vim-nix)

Support for writing [Nix expressions](http://nixos.org/nix/manual/#chap-writing-nix-expressions) in vim.

Features included so far:

* Syntax highlighting for Nix
* Filetype detection for `.nix` files
* Automatic indentation


## Installation

### Plugin managers

The most common plugin managers include [vim-plug][vim-plug],
[NeoBundle][neobundle], [Vundle][vundle] and [pathogen.vim][pathogen].

With pathogen.vim, just clone this repository inside `~/.vim/bundle`:

```bash
git clone https://github.com/LnL7/vim-nix.git ~/.vim/bundle/vim-nix
```

With the other plugin managers, just follow the instructions on the homepage of
each plugin. In general, you have to add a line to your `~/.vimrc`:

```viml
" vim-plug
Plug 'LnL7/vim-nix'
" NeoBundle
NeoBundle 'LnL7/vim-nix'
" Vundle
Plugin 'LnL7/vim-nix'
```

### Manual installation

Copy the contents of each directory in the respective directories inside
`~/.vim`.


[vim-plug]: https://github.com/junegunn/vim-plug
[vundle]: https://github.com/gmarik/Vundle.vim
[neobundle]: https://github.com/Shougo/neobundle.vim
[pathogen]: https://github.com/tpope/vim-pathogen
