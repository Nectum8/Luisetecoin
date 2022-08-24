
Debian
====================
This directory contains files used to package luisetecoin-qt
for Debian-based Linux systems. If you compile luisetecoind/luisetecoin-qt yourself, there are some useful files here.

## pivx: URI support ##


luisetecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install luisetecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your luisetecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

luisetecoin-qt.protocol (KDE)

