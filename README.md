## .vimrc file

Add this to `.vimrc` in home directory:

```
if filereadable("/Users/<username>/.../vim_configuration/vimrc_extras")   
  source /Users/<username>/.../vim_configuration/vimrc_extras
endif                                       
                                            
if filereadable("/Users/<username>/.../vim_configuration/rest.vim")
  source /Users/<username>/.../vim_configuration/rest.vim
endif                                       

```

Note that `/home/<username>` is used on Ubuntu and `/Users/<username>` on OS X.

The `rest` content is not in use now.

[end]
