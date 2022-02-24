# vimrc
Customized vimrc file that includes a number of tweaks both visual and functional.

This vimrc has a color scheme baked into it, along with tab auto completion and begins seeking as soon you begin a search. Since theme and functions are all contained in the rc file, it is portable and can quickly and easily be used on the fly even in terminal sessions on remote hosts.

To test the configuration or use in a remote session without modifying local files, curl can be used for example:

`$ vim -Nu <(curl -s https://raw.githubusercontent.com/GilbertStawny/vimrc/main/.vimrc) somefile`

Please be mindful using curl in a process redirect,  this practice is generally frowned upon as security issue as you don't know what you're curling right into a command.
