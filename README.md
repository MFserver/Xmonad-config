# Xmonad-config

This is my basic Xmonad configuration. It features 11 named workspaces operated by one hand on a normal QWERTY keyboard using Caps lock as a switcher, is lightning-fast, pretty intuitive and quick-starts applications using keyboard commands. I've found it to be quite versatile. 

## Requirements

    xmonad (obviously)
    xmobar
    stalonetray (gives icons)
    conky
    dmenu (for starting applications) (might be optional depending on your definition of 'optional')

### Optional

    Chromium (the web browser)
    Dolphin (my file manager of choice)
    Xterm (terminal)
    Pulseaudio
    scrot (screenshots)
    Kate (text editor for code files and such)

Some other applications have support in my config but are by no means required to run it. Like, for example, League of Legends. 

## What's in here, and how to use it

### .conkyrc

Simply copy to your home directory and start conky to test it. 

    cp .conkyrc ~/.conkyrc
    conky

### .xinitrc

This file is sourced by the X server when it starts. It might need modifications for your system, or you could just open the file and copy what you like into your existing `~/.xinitrc`. 

### .xmobarrc.hs

The configuration of xmobar. Mine is placed in my home directory, but you can place it anywhere and name it whatever you like, as long as you update the location in the xmonad config. 

    cp .xmobarrc.hs ~/.xmobarrc.hs

### .xmodmap

Kustom keyboard shortcuts can be found here. Simply copy to your home. 

    cp .xmodmap ~/.xmodmap
