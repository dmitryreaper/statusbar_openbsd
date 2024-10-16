# statusbar-openbsd

Simple program that can update the dwm window manager status line for
OpenBSD.

It sets the X root window to battery status and charge, a CPU
temperature,volume, and prints a timestamp, then sleeps for 2 seconds and
repeats. dwm picks this up and displays it in its status bar.
