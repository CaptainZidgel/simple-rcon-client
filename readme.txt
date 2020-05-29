If you wish to build or run from command-line:
* You will need the rcon library from python-valve. Full package is https://github.com/serverstf/python-valve but you can install just what you need with:
* curl -R -O https://raw.githubusercontent.com/serverstf/python-valve/master/valve/rcon.py
* I build it this way because I assume it will keep the size of the package small. Not sure though! :)

* You will need cx_Freeze to build.
* execute make.bat
* Dependencies for the rcon module that don't come standard are things called docopt, six, and monotonic. If you're using Python >=3.3 you can replace import monotonic with import time (time is stdlib) and replace monotonic.monotonic() with time.monotonic()

This program is intended for distribution to those without a Python installation. If you have the tools to build this, you don't need to use it all.
Install python-valve and you can start an RCON shell or even call single commands from the command line. See https://python-valve.readthedocs.io/en/latest/rcon.html#command-line-invocation

This project is really simple. Honestly, the only reason I have this as a github is so I can use the releases function.