# My Awesome WM config

Custom config for [Awesome WM](http://awesome.naquadah.org).

This config is compatible with AwesomeWM version 4.3 and newer.

## Screenshot

In future release

## Description

Advanced user config for `awesome` consist of a bunch of new widgets, 
features, tiling schemes, and some reworked standard widgets. 
This repository provide only config and instruction
Main code base can be found in `redflat` submodule.

#### Core Features

* Full color control, including widget icons;
* True vector scaling for widget icons (gdkpixbuf required);
* New unique panel widgets and some reworked from standard lib;
* A pack of desktop widgets;
* A pack of widgets for applications control (quick launch, application switch, ect);
* Several minor improvements for menu widget;
* Alternative titlebars with several visual schemes;
* Active screen edges;
* Keys sequences;
* Advanced hotkeys helper;
* Special window control mode which allow use individual hotkeys for different layouts;
* New tiling layout to build your placement scheme manually;

## Dependencies

#### Main

* Awesome WM 4.3+
* BetterlockScreen (Aur or github)
* rofi-menus (Aur)

#### Widgets

| widget                 | type     | utility             |
| ---------------------- | -------- | ------------------- |
| unread mail indicator  | panel    | curl/user scripts   |
| system updates         | panel    | apt-get*            |
| volume control         | panel    | pacmd               |
| brightness control     | floating | xbacklight          |
| mpris2 player          | floating | dbus-send           |
| CPU temperature        | desktop  | lm-sensors          |
| HDD temperature        | desktop  | smartctl**          |
| Nvidia GPU temperature | desktop  | nvidia-smi/optirun  |
| torrent info           | desktop  | transmission-remote |

\* Actually any one-liner written for your package manager.  
\*\* Should be configured to run from user.

## Installation and Usage

#### Installation

Copy scripts to WM setting folder. 
Simple way to do so with `git`

```shell
$ git clone https://github.com/yuky2020/awesome-config.git ~/.config/awesome --recursive
```

Then give a tray 