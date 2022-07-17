# DotFiles

These configuration files are used on my arch linux machine for ricing i3/polybar and a few other things, these are updated frequently so make sure to check back for updates.
In order to use this download/git clone this repo as a zip and extract the folders to your .config directory

The end result should look like this

![](screenshots/screenshot.png)


THINGS TO NOTE: the KITTY terminal config is not complete and isnt well made at the moment, this will improve in the future, for now feel free to use the terminator config instead.

Please remember to change ``set $monitor1`` ```set $monitor2``` ```exec_always xrandr --output --mode 1920x1080 --rate 240.00 --primary --left-of DP-2```
and ```workspace $ws1 output $monitor1``` to whatever corosponds to your system/setup, you can run xrandr in the terminal to find out what your monitors are listed as.

You may also need to change the fonts used in the polybar config as the font i use is a paid font.

Some things in this config may be scuffed but please bare with me as i try to clean it up.

You will need to have the rofi-emoji package installed for the emoji picker to work.
-----------------------------------------------------------------------------------------------------------------------------------------------------------

The CLI tools used in the screenshot are as follows: [Unimatrix](https://github.com/will8211/unimatrix) [Htop](https://htop.dev/) [Cava](https://github.com/karlstav/cava) [Pokeshell](https://github.com/acxz/pokeshell) [Afetch](https://github.com/13-CF/afetch) 
