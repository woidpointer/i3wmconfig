## Installation packages

```
$ sudo apt install meson dh-autoreconf libxcb-keysyms1-dev libpango1.0-dev \
    libxcb-util0-dev xcb libxcb1-dev libxcb-icccm4-dev libyajl-dev libev-dev \
    libxcb-xkb-dev libxcb-cursor-dev libxkbcommon-dev libxcb-xinerama0-dev \
    libxkbcommon-x11-dev libstartup-notification0-dev libxcb-randr0-dev \
    libxcb-xrm0 libxcb-xrm-dev libxcb-shape0 libxcb-shape0-dev

$ sudo apt install i3 rofi polybar nautilus

mkdir build cd build
meson --prefix /usr/local
ninja
sudo ninja install
```

## Install

```
$ rake config:i3

```
