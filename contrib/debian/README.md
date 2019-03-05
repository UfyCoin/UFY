
Debian
====================
This directory contains files used to package ufyd/ufy-qt
for Debian-based Linux systems. If you compile ufyd/ufy-qt yourself, there are some useful files here.

## ufy: URI support ##


ufy-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ufy-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ufyqt binary to `/usr/bin`
and the `../../share/pixmaps/ufy128.png` to `/usr/share/pixmaps`

ufy-qt.protocol (KDE)

