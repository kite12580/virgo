virgo
=====
Virtual Desktop Manager for Windows

[Download here](https://github.com/kite12580/virgo/releases/latest/download/virgo.zip)

Features:
- resource friendly, exe is <12kb on disk and uses <1mb memory while running
- 2 virtual desktops
- shows only a tray icon with the number of the desktop you are on, in a
  different color per desktop
- restores focus to the last active window when switching desktops
- shows all windows when you log off or shut down

Hotkeys:

        WIN + ` -> switches between desktop 1 and 2

Left-click the tray icon to switch to the next desktop. Right-click it to
switch to or move the active window to a desktop, start/stop handling of the
hotkey, or exit.

the nerds can build it with

        git clone https://github.com/kite12580/virgo.git
        cd virgo
        make

If you do not have gcc/make installed you can change that doing following

1. go to http://msys2.github.io/ and install it according to the instructions there
2. open msys2 shell and install mingw-w64-i686-gcc and mingw-w64-i686-make using pacman
3. duplicate C:\msys32\mingw32\bin\mingw32-make.exe and name it make.exe
