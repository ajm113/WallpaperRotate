# WallpaperRotate
*Randomly rotates wallpaper of user using feh.*

## Platforms

Anything that runs Shell and feh. (Unix/Linux)
https://feh.finalrewind.org/


## Install

**Please make sure feh is install first!**
https://feh.finalrewind.org/

1. Clone repo.
2. Run `$ sudo cp wr /usr/bin/`
3. Then run `$ sudo chmod +x /usr/bin/wr` Makes wr as a executable.

## Running

- Run `$ wr` in any directory with images or put it in a startup script!
- Run WallpaperRotate with path! `$ wr ~/Pictures`.
- Run custom commands to feh! `$ wr ~/Pictures --bg-tile`

## F.A.Q

### What is feh?

*feh is an X11 image viewer aimed mostly at console users. Unlike most other viewers, it does not have a fancy GUI, but simply displays images. It is controlled via commandline arguments and configurable key/mouse actions.* -- feh Website

### I can't copy to /usr/bin/wr! File already exists!

You may need to change the filename to something else. Name it `wallpaperrotate` or something easy to remember or tab to like `wrr`.
