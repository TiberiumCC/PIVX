
Debian
====================
This directory contains files used to package tiberiumd/tiberium-qt
for Debian-based Linux systems. If you compile tiberiumd/tiberium-qt yourself, there are some useful files here.

## tiberium: URI support ##


tiberium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tiberium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tiberiumqt binary to `/usr/bin`
and the `../../share/pixmaps/tiberium128.png` to `/usr/share/pixmaps`

tiberium-qt.protocol (KDE)

