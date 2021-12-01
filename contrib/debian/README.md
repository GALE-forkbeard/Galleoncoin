
Debian
====================
This directory contains files used to package galleoncoind/galleoncoin-qt
for Debian-based Linux systems. If you compile galleoncoind/galleoncoin-qt yourself, there are some useful files here.

## galleoncoin: URI support ##


galleoncoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install galleoncoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your galleoncoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/galleoncoin128.png` to `/usr/share/pixmaps`

galleoncoin-qt.protocol (KDE)

