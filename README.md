# gtk4 on macOS

This is my first build of GTK 4 using JHBuild. For science!

## details

I'm trying to stay as true as possible with [gtk-osx](https://gitlab.gnome.org/GNOME/gtk-osx), but I prefer my own setup routine instead of [`gtk-osx-setup.sh`](https://gitlab.gnome.org/GNOME/gtk-osx/-/blob/master/gtk-osx-setup.sh). I presume that accounts for the change in `pygments` that I have to do in [`modulesets-stable.patch`](modulesets-stable.patch) while the other things need to be reported upstream.

## license

[GPL-2.0-or-later](LICENSE)