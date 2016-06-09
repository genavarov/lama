
Debian
====================
This directory contains files used to package litecoind/lamacoin-qt
for Debian-based Linux systems. If you compile litecoind/lamacoin-qt yourself, there are some useful files here.

## litecoin: URI support ##


Lamacoin.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Lamacoin.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Lamacoin binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

Lamacoin.protocol (KDE)

