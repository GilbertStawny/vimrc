# vimrc
Portable and customized vimrc file that includes a number of tweaks both visual and functional.

![screenshot](https://github.com/lacework-support-tools/vimrc/blob/main/screen.png?raw=true)

This vimrc has a color scheme baked into it, along with tab auto completion and begins seeking as soon you begin a search. Since theme and functions are all contained in the rc file, it is portable and can quickly and easily be used on the fly even in terminal sessions on remote hosts.

To backup your current vimrc and replace it, simply run:

`$ git clone git@github.com:lacework-support-tools/vimrc.git`  
`$ mv ~/.vimrc{,-bak} && mv ./vimrc/.vimrc ~/.vimrc`

To test the configuration without replacing your existing vim configuration, you can use the -Nu flag to manually specify the configuration file:

`$ vim -Nu ../vimrc/.vimrc somefile`

You can also set a temporary alias for your session:

`alias vim='vim -Nu ../vimrc/.vimrc'`

If you would like to also add the nifty status bar displayed at the bottom of the screenshot, please follow instructions included with the 'airline' release. Please note that this makes the vimrc no longer portable as it depends on a plugin to be installed along with fonts.
