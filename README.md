# Alacritty Kinda Solarized Theme

This is a custom style configuration file for [Alacritty terminal emulator](https://github.com/alacritty/alacritty) for Windows in a toml format, inspired by Ethan Schoonover's Solarized light theme. It can be used as an example for those, who do not understand how to write a toml config file or as a pre-manufactured style preferences for your Alacritty.

## What's within

This file configures Alacritty according to my very own opionated, though not-too-uncommon preferences.

It sets the window starting dimentions to be 100x25 ([more on what it means here](https://alacritty.org/config-alacritty.html#s7)). 
Position of the window is set to be in the middle of the screen for my device, [think of the most convinient position for you](https://alacritty.org/config-alacritty.html#s8), or let the window manager place the window by setting it to None or removing the entry.
The app is retitled as "terminal".

!**IMPORTANT**

**Due to fonts' differences, this config would not work correcrtly on Linux devices. Replace Consolas with a font of your choice, like monospace, which is Alacritty's default for Linux and BSD.** 

Cursor is changed for a blinking block, with the timeout of 2 seconds. 
Mouse is hidden while typing.

## Colors

Colors for the theme are inspired by [Ethan Schoonover's Solarized light theme](https://ethanschoonover.com/solarized/). 
While drawning inspiration from it, I tweaked the colors according to my aesthetic preferences.

Cheat sheet specifying original Solarized hex codes can be found [here](https://www.zovirl.com/2011/07/22/solarized_cheat_sheet/).

## Recommendations 

I am not a big fan of replacing standard keybinding with ones of your choice, I rather prefer learning the provided ones, but you can modify them [as you wish](https://alacritty.org/config-alacritty.html#s90).

Also, I highly recommend setting your [standard working directory](https://alacritty.org/config-alacritty.html#s2) and selecting [your favorite shell](https://alacritty.org/config-alacritty.html#s1).  

## More info

Alacritty: https://alacritty.org/index.html
Alacritty's repo: https://github.com/alacritty/alacritty
Full configuration instructions: https://alacritty.org/config-alacritty.html
Ethan Schoonover's Solarized theme: https://ethanschoonover.com/solarized/
Ethan Schoonover's Solarized theme repo: https://github.com/altercation/solarized
TOML: https://toml.io/en/
