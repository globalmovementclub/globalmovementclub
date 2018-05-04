
Debian
====================
This directory contains files used to package grandmastercoind/grandmastercoin-qt
for Debian-based Linux systems. If you compile grandmastercoind/grandmastercoin-qt yourself, there are some useful files here.

## grandmastercoin: URI support ##


grandmastercoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install grandmastercoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your grandmastercoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/grandmastercoin128.png` to `/usr/share/pixmaps`

grandmastercoin-qt.protocol (KDE)

