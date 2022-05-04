# Vimtutor Pro

working on progress.

To disable customized version of Vim, launch vim with these options.
```bash
vim -u NONE -N
```

Some of Vim's built-in features are implemented with Vim script, which is that they will only work when plugins are enabled.
To activate Vim's built-in plugins with a minimum set up, make a file called min_set.vim, and launch vim with these options below.
```bash
echo "set nocompatible" > min_set.vim
echo "filetype plugin on" >> min_set.vim
vim -u min_set.vim
```

To check the version of Vim, you can run the command below when using the Vim.
```bash
:version
```

# dot command
`.` command is to repeat the last change.

The `x` command deletes the character under the cursor.
