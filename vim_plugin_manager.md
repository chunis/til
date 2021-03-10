# Vim Plugin Manager

- https://github.com/junegunn/vim-plug
- https://github.com/VundleVim/Vundle.vim

## Notes for vim-plug
1. Install by: `curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim`
2. Config it by adding below lines to file `~/.vimrc`:
```
" Plugins will be downloaded under the specified directory.
call plug#begin('~/.vim/plugged')

" Declare the list of plugins.
Plug 'ollykel/v-vim' " this is syntax highlight for VLang

" List ends here. Plugins become visible to Vim after this call.
call plug#end()
```
3. Restart vim, and run from vim with "PlugInstall", then check the result with "PlugStatus"
