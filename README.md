# mapwacom

Maps a wacom tablet to an external monitor. If no external monitor is found, then maps to internal monitor.

## Installation

```
$ git clone https://github.com/mkomod/mapwacom
```

Then append to `$PATH`

Temporary (until reboot)

```
$ cd mapwacom
$ export PATH=$PATH:$(pwd)
```

or edit your shell rc directly


## Usage

```
$ source mapwacom
```

Alternatively, a keybinding can be added to something like `xbindkeys` such that the script is ran after a hotkey is pressed.


