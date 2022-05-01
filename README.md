# Vimtutor Pro

working on progress.

To disable customized version of Vim, launch vim with these options.
```bash
$ vim -u NONE -N
```

Some of Vim's built-in features are implemented with Vim script, which is that they will only work when plugins are enabled.
To activate Vim's built-in plugins with a minimum set up, make a file called min_set.vim, and launch vim with these options below.
```bash
$ echo "set nocompatible\nfiletype pluging on" > min_set.vim
$ vim -u min_set.vim
```
