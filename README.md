# xwayland4tewmux

Xwayland packages that were moved into disabled packages...

# Installation

```
wget https://github.com/suhan-paradkar/xwayland4tewmux/releases/download/xwayland/libwayland-protocols_1.17-4_$(dpkg --print-architecture).deb
wget https://github.com/suhan-paradkar/xwayland4tewmux/releases/download/xwayland/libwayland_1.19.0_$(dpkg --print-architecture).deb
wget https://github.com/suhan-paradkar/xwayland4tewmux/releases/download/xwayland/xwayland_1.20.5-6_$(dpkg --print-architecture).deb
pkg in ./libwayland-protocols_1.17-4_$(dpkg --print-architecture).deb ./libwayland_1.19.0_$(dpkg --print-architecture).deb ./xwayland_1.20.5-6_$(dpkg --print-architecture).deb
```

# Usage

```
export XDG_RUNTIME_DIR=$TMPDIR
Xwayland -ac :1 &
```
