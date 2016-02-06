metai3
======

metai3 is a meta script that controls i3 functions. It gives you additional
useful functions for different i3 workflows.

Features
--------

metai3 makes heavy use of interactive dialogs using 'rofi'.

metai3 currently supports the following commands:

* focus-next-output
* move-container-to-next-output
* move-workspace-to-next-output
* pull-window
* push-container
* rename-workspace
* focus-workspace
* new-workspace

Requirements
------------

metai3 needs i3-py and rofi installed.

To install metai3, just use it as a binary in your bindings:
```
bindsym Mod4+p exec ~/bin/metai3 focus-next-output
```
