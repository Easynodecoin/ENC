
Debian
====================
This directory contains files used to package easynodecoind/easynodecoin-qt
for Debian-based Linux systems. If you compile easynodecoind/easynodecoin-qt yourself, there are some useful files here.

## easynodecoin: URI support ##


easynodecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install easynodecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your easynodecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/easynodecoin128.png` to `/usr/share/pixmaps`

easynodecoin-qt.protocol (KDE)

