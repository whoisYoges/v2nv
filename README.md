# v2nv

I switched to neovim from vim. So v2nv means vim to nvim

Basically, the configuration for vim and neovim is almost same you just need to edit some paths.

![Screenshot-2022-16-06-10-44-04](https://user-images.githubusercontent.com/51807726/174012656-7456cfc1-b76f-46e1-8303-9e65fe178b56.png)

I just seprated config into three different files so that it is easier and more convenient to read understand and use.

- [init.vim](init.vim) is the main configuaration file. rename to .vimrc if you use vim.
- [key-bindings.vim](key-bindings.vim) is a separate file configured store key binding settings.
- [plugins.vim](plugins.vim) is a separate file configured to store plugin settings. All the plugins, p;ugin settings and plugin specific keybindiings are stored here.

*note:* I am using [vim-plug](https://github.com/junegunn/vim-plug) to manage all my plugins.

All the key bindings are stated in [hotkeys](hotkeys).
