This repository hosts alarm/xf86-video-odroid-xu3 PKGBUILD. It allows you to build the xf86-video-odroid-xu3 package which provides the Xorg ArmSoc driver for the ODROID XU3/XU4/HC1/HC2/MC1 (v1.4.1 from Hardkernel).

The goal of this project is to provide a complete driver stack identical to that provided by Hardkernel. Maybe this code can be pushed into the official repository later...

Tested with XU4 only (don't have XU3/HC1/HC2/MC1). Work in progress. Feedback is welcome.

## Usage
* sudo pacman -S base-devel git
* git clone https://github.com/ffaille/alarm-xf86-video-odroid-xu3.git
* cd alarm-xf86-video-odroid-xu3
* makepkg --syncdeps --noconfirm --log
* sudo pacman -U ./alarm-xf86-video-odroid-xu3-1.4.1-1-armv7h.pkg.tar.xz