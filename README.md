# Tewmux-disabled

Awesome packages that were moved into disabled packages...
Also includes packages that are created by me and some packages added by @thunder-coding after very hard work for testers...
Currently hosted by @leapofazzam123 and @yisus7u7


# Installation

For example.. to install xwayland....

```
wget https://github.com/suhan-paradkar/tewmux-disabled/releases/download/xwayland/libwayland-protocols_1.17-4_$(dpkg --print-architecture).deb
wget https://github.com/suhan-paradkar/tewmux-disabled/releases/download/xwayland/libwayland_1.19.0_$(dpkg --print-architecture).deb
wget https://github.com/suhan-paradkar/tewmux-disabled/releases/download/xwayland/xwayland_1.20.5-6_$(dpkg --print-architecture).deb
pkg in ./libwayland-protocols_1.17-4_$(dpkg --print-architecture).deb ./libwayland_1.19.0_$(dpkg --print-architecture).deb ./xwayland_1.20.5-6_$(dpkg --print-architecture).deb
```
# Available packages

```
Jenkins CI
Apache ANT
XWayland, with all its dependencies
Mesa, modded
gobject-introspection
gl4es
modded util-linux, to include libmount support
Extra xorg libs... the ones that are supplementary to T:X11
Alsa-lib.... with static libs
Alsa-plugins.... with static libs
Alsa-utils
Qemu, with spice support
Spice-server and spice-protocol
Gradle
Groovy
Nodejs (Available versions: 16.6.1, 16.9.1)
```

# Build

You wanna build it yourself?? The config files are here....
http://github.com/suhan-paradkar/my-tewmux-build-config

Patches of some of the debs are released along with the debs in release
