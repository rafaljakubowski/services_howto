# Python Services. HowTo
The repo devoted to gathering information about building sytem services - most likely only Linux will be considered.
More like a dirty notepad than real how-to.

## Introduction

Building linux services might be a challenging tasks. This set of notes has been created to keep the most important information gathered during building some of them kept in one place, minimizing the chance of loosing data.

It's not supposed to be helpful, but in case it is... Well, it is.

## Useful links

### Basic info
https://github.com/torfsen/python-systemd-tutorial - how to setup basic systemd config

https://en.wikipedia.org/wiki/Runlevel#Linux - Wiki runlevel table

https://medium.com/@benmorel/creating-a-linux-service-with-systemd-611b5c8b91d6 - quite nice tutorial, based on a simple PHP script

### Pythonish stuff
https://docs.python.org/3/howto/sockets.html - socket handling basics

https://realpython.com/python-sockets/

http://zetcode.com/python/socket/

https://pythonprogramming.net/pickle-objects-sockets-tutorial-python-3/

https://stackoverflow.com/questions/39817641/how-to-send-a-json-object-using-tcp-socket-in-python - interesting SO discussion

https://stackoverflow.com/questions/1603109/how-to-make-a-python-script-run-like-a-service-or-daemon-in-linux - and this SO is even better, witha base from here: https://web.archive.org/web/20160320091458/http://www.jejik.com/files/examples/daemon3x.py and here: https://web.archive.org/web/20160305151936/http://www.jejik.com/articles/2007/02/a_simple_unix_linux_daemon_in_python/

https://stackoverflow.com/questions/32404/how-do-you-run-a-python-script-as-a-service-in-windows - in case someone needs to make a service working on Windows

https://python-service.readthedocs.io/en/stable/ - Python `service` package

https://pypi.org/project/python-daemon/ - Python `daemon` library

### `systemd` stuff
https://www.linux.com/training-tutorials/understanding-and-using-systemd/

### Some oldish stuff
https://bash.cyberciti.biz/guide/Service_command - still popular
