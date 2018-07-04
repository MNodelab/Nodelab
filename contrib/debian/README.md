
Debian
====================
This directory contains files used to package nodelabd/nodelab-qt
for Debian-based Linux systems. If you compile nodelabd/nodelab-qt yourself, there are some useful files here.

## nodelab: URI support ##


nodelab-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nodelab-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nodelab-qt binary to `/usr/bin`
and the `../../share/pixmaps/nodelab128.png` to `/usr/share/pixmaps`

nodelab-qt.protocol (KDE)

