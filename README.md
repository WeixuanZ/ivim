# iVim Configuration and Plugins

iVim does not have git (cannot install plugins using vim-plug), and Files does
not show hidden files (downloading and unzipping manually is painful), so this
is a workaround using Working Copy.

This repository should be cloned to a Working Copy synced folder: `On my
iPad/iVim/ivim`. Then move `.vimrc`, containing

```vim
source ~/ivim/vim-plug/plug.vim
source ~/ivim/dotfiles/vim/.vimrc
```

one directory up. vim-plug and the main vimrc (at
[WeixuanZ/dotfiles](https://github.com/WeixuanZ/dotfiles), included also as
a submodule) are sourced.

Only the plugins included as submodules will be loaded by vim-plug. These are
a subset of the ones included in the main vimrc, since not all of them are
supported due to iOS limitations.
