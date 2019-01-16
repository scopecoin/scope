
Debian
====================
This directory contains files used to package scoped/scope-qt
for Debian-based Linux systems. If you compile scoped/scope-qt yourself, there are some useful files here.

## scope: URI support ##


scope-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install scope-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your scope-qt binary to `/usr/bin`
and the `../../share/pixmaps/scope128.png` to `/usr/share/pixmaps`

scope-qt.protocol (KDE)

