# MPV-MordenX
Pre-configured MPV for anime to save time, be more convenient and act as my backup.
[![OSC](https://github.com/cyl0/MordenX/blob/main/preview.png "OSC")](https://github.com/cyl0/mpv-osc-morden-x "OSC")
## Installation
- Clone this repository or download and unzip wherever you want.
- Run `mpv-install.bat` as administrator located in the `installer` folder.
- Modify [`mpv.conf`](https://github.com/Raventhicc/MPV-Morden-X/blob/main/portable_config/mpv.conf "mpv.conf")  according to your preferences.

## Included Scripts
- [auto-profiles](https://github.com/Moodkiller/MPV-Made-Easy/blob/master/scripts/auto-profiles.lua "auto-profiles")
- [autoload](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autoload.lua "autoload")
- [cycle-commands](https://github.com/CogentRedTester/mpv-scripts/blob/master/cycle-commands.lua "cycle-commands")
- [cycle-profile](https://github.com/CogentRedTester/mpv-scripts/blob/master/cycle-profile.lua "cycle-profile")
- [cyl0's mordenx](https://github.com/cyl0/mpv-osc-morden-x "mordenx")
- [playlistmanager](https://github.com/jonniek/mpv-playlistmanager "playlistmanager")
- [videoclip](https://github.com/Ajatt-Tools/videoclip "videoclip")

## Included Shaders
- [Anime4k](https://github.com/bloc97/Anime4K "Anime4k") - Check Keybinds.
- [KrigBilateral-new](https://github.com/Ichunjo/mpv-config/tree/master/Shaders "KrigBilateral-new") - Activates automatically whenever pixel format is `yuv420p12` or `yuv420p10` or `yuv420p`.
- [KrigBilateral-new-444](https://github.com/Ichunjo/mpv-config/tree/master/Shaders "KrigBilateral-new-444") - Activates automatically whenever pixel format is `yuv444p10`.
- [nnedi3-nns128-win8x4](https://github.com/bjin/mpv-prescalers/blob/master/nnedi3-nns128-win8x4.hook "nnedi3-nns128-win8x4") (default) - Activates automatically whenever content resolution is lower than screen resolution.
- [nnedi3-nns256-win8x4](https://github.com/bjin/mpv-prescalers/blob/master/nnedi3-nns256-win8x4.hook "nnedi3-nns256-win8x4") - Included.
## Custom Keybinds
**General**
- `l` *cycle-values loop "yes" "no"*

**Audio**
- `WHEEL_UP`     *add volume 2*
- `WHEEL_DOWN`   *add volume -2*
- `WHEEL_LEFT`   *seek 10*
- `WHEEL_RIGHT`  *seek -10*

**Filtering**
- `d` *cycle deband*
- `h` *cycle deinterlace*

**Anime4k**
- `CTRL+1` *"Anime4K: Mode A (HQ)"*
- `CTRL+2` *"Anime4K: Mode B (HQ)"*
- `CTRL+3` *"Anime4K: Mode C (HQ)"*
- `CTRL+4` *"Anime4K: Mode A+A (HQ)"*
- `CTRL+5` *"Anime4K: Mode B+B (HQ)"*
- `CTRL+6` *"Anime4K: Mode C+A (HQ)"*
- `CTRL+0` *"Remove Shaders"*

## Helpful Links
- https://mpv.io/manual/stable/
- https://github.com/rossy/mpv-install
- https://iamscum.wordpress.com/guides/videoplayback-guide/
- https://iamscum.wordpress.com/guides/videoplayback-guide/mpv-conf/
- https://github.com/mpv-player/mpv/wiki/User-Scripts
