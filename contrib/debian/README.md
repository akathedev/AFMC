
Debian
====================
This directory contains files used to package nodepayd/nodepay-qt
for Debian-based Linux systems. If you compile nodepayd/nodepay-qt yourself, there are some useful files here.

## nodepay: URI support ##


nodepay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nodepay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nodepay-qt binary to `/usr/bin`
and the `../../share/pixmaps/nodepay128.png` to `/usr/share/pixmaps`

nodepay-qt.protocol (KDE)

