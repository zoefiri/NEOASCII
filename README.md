# Neofetch ASCII!

This is a collection of ASCII art meant to be used in Neofetch, for those that don't wish to participate in distro patriotism.

to use these simply run `neofetch --ascii path/to/txt -ascii_colors 1 2 3 4 5 6`
the order of the numbers in `ascii_colors` will determine what colors are used in the ASCII art. 

If you would like to make some ASCII art to contribute or for yourself, there's a bit of info on it at https://github.com/dylanaraps/neofetch/wiki/Custom-Ascii-art-file-format but there is one thing that is useful in making ASCII art for neofetch that isn't there, you don't want to use unicode escapes but rather the actual characters because neofetch will acommodate for the full space taken up by the unicode escapes and this will usually result in all the other neofetch text being pushed offscreen.
