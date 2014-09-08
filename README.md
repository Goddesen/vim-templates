vim-templates
=============

```vimscript
augroup templates
    au!
    " read in templates files
    autocmd BufNewFile *.* silent! execute '0r ~/.vim_runtime/vim-templates/template.'.expand("<afile>:e")
augroup END
```
