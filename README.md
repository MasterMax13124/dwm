# dwm - dynamic window manager

This repo contains my personal modified version of [dwm](https://dwm.suckless.org/). This repo is intended to be used together with my Arch Linux [dotfiles](https://github.com/MasterMax13124/dotfiles).

## Features of this build

- Gaps between windows, using this [patch](https://dwm.suckless.org/patches/vanitygaps/)
- Support for volume control buttons, from this [gist](https://gist.github.com/palopezv/efd34059af6126ad970940bcc6a90f2e)
- Support for brightness controls, through xbacklight, very similar to gist mentioned above
- Gruvbox colors from [here](https://github.com/plasmoduck/themes/blob/master/gruvbox-hard/colors-wal-dwm.h)
- Shortcut for screen lock using [slock](https://tools.suckless.org/slock/)

## Other changes
I am still playing around with different shortcuts and key combinations, but most notably I've switched the dwm mod key from left `alt` to left `super` (see [here](https://dwm.suckless.org/customisation/windows_key/)), remapped the quit action to `Super + Q` and made `Super + Shift + Enter` open `kitty` instead of `st`. The default font in my build is [Fira Code Nerd Font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/FiraCode), while [noto-cjk](https://www.google.com/get/noto/help/cjk/) is used to display the dwm tags and modes with japanese characters. There is also a shortcut that triggers a duckduckgo-searching script of mine, which you should probably remove, if you wanna build with my config, just delete all lines that include the text `duckselectfirefox`. I've also recently added a shortcut for my bookmarks script (`firefoxbookmarks`), which you can also delete for your use.

## Additional tools
This is just a list of other stuff I use with this setup, mainly for me to reference in the future:
- [kitty](https://sw.kovidgoyal.net/kitty/), my favorite terminal on Linux and macOS 
- [dmenu](https://tools.suckless.org/dmenu/), which serves as the default application launcher for dwm
- [nitrogen](https://github.com/l3ib/nitrogen/), which sets my wallpaper
- [picom](https://github.com/yshui/picom), for that sweet transparency on my terminal etc
- [slock](https://tools.suckless.org/slock/), a super simple lock screen, also from the suckless people
- [my diy status script](https://github.com/MasterMax13124/dotfiles/blob/main/Arch/scripts/xsetroot-script-thinkpad.sh), which uses xsetroot to display system info, like the volume, brightness and current time
- [lxappearance](https://github.com/lxde/lxappearance), to change themes for GTK applications
