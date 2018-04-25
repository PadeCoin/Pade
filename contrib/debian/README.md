
Debian
====================
This directory contains files used to package paded/pade-qt
for Debian-based Linux systems. If you compile paded/pade-qt yourself, there are some useful files here.

## pade: URI support ##


pade-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pade-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pade-qt binary to `/usr/bin`
and the `../../share/pixmaps/pade128.png` to `/usr/share/pixmaps`

pade-qt.protocol (KDE)

