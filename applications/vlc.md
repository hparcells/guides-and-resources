# VLC Media Player
> Tips for using VLC media player.

## Table of Contents
- [VLC Media Player](#vlc-media-player)
  - [Table of Contents](#table-of-contents)
  - [Folders Inside of Folders](#folders-inside-of-folders)

## Folders Inside of Folders

In some cases, you might want to play a folder of songs. If there are folders of music inside of the folder. VLC won't always open those folders to play them. To fix this, append `--recursive="expand"` to the end of the VLC command.

```
"C:\Program Files\VideoLAN\VLC/vlc.exe" "E:\Music\" -L -Z --recursive="expand"
```
