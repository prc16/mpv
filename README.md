## Requirements

* official MPV Player: https://mpv.io/ - [download MPV v3](https://sourceforge.net/projects/mpv-player-windows/files/64bit-v3/)

## Configuration for MPV v3

* Download the [latest release](https://github.com/prc16/mpv/releases)
* Extract the contents of mpv directory next to `mpv.exe`
    * (i.e. `mpv.conf` file should be next to `mpv.exe`)
* Delete `input.conf` if desired (custom keybindings)
* In the `mpv.conf` file toggle the configuration options as per your requirement.
* If your GPU cannot handle the shaders in `mpv.conf`, comment out the include line for `mpv_shaders.conf`