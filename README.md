# tex-conceal.vim

This plugin extends the Conceal feature of Vim for LaTeX.

### Without conceal
<img src="https://github.com/KeitaNakamura/tex-conceal.vim/blob/master/normal.png" width="800">

### With conceal
<img src="https://github.com/KeitaNakamura/tex-conceal.vim/blob/master/conceal.png" width="800">

### With conceal and this plugin
<img src="https://github.com/KeitaNakamura/tex-conceal.vim/blob/master/conceal_plugin.png" width="800">

### Output
<img src="https://github.com/KeitaNakamura/tex-conceal.vim/blob/master/output.png" width="800">

## Installation
To install just put the following line in `vim:~/.vimrc`.
### for Vundle
`Plugin 'KeitaNakamura/tex-conceal.vim'`
### for VimPlug
`Plug   'KeitaNakamura/tex-conceal.vim'`

## Recommend settings
Put the following lines inside `vim:~/.vimrc`, it is recommended to post these after the `call plug#end()`.
```
set conceallevel=2
let g:tex_conceal="abdgm"
```
If not already set, it is also recommended that the following lines are added.
```
set encoding=utf-8
set renderoptions=type:directx
```

