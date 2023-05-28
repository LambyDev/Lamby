
Debian
====================
This directory contains files used to package lambyd/lamby-qt
for Debian-based Linux systems. If you compile lambyd/lamby-qt yourself, there are some useful files here.

## lamby: URI support ##


lamby-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lamby-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lamby-qt binary to `/usr/bin`
and the `../../share/pixmaps/lamby128.png` to `/usr/share/pixmaps`

lamby-qt.protocol (KDE)

