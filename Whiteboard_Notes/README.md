# WHITEBOARDS NOTES
--------------------

## day 001 - [Python Basics](Whiteboard_notes_Day1.jpg)

### What is Python:
Python is a widely used high-level programming language for general-purpose programming

### Who Created Python:
created by Guido van Rossum and first released in 1991.

### Python features: 
- Dynamic type system.
- Automatic memory management.
- Supports multiple programming paradigms (object-oriented, imperative, functional programming,
and procedural styles).
- Clear, simple and conventional syntax.
- Has a large and comprehensive standard library.
- Used in a lot of context applications.
- Has a Large community.
- IS FREE, FUN AND EASY TO LEARN.

### Typical Programs:
- CLI (Command Line Interpreter)
- GUI Desktop applications
- Web Backend Applications
- Robots and hardware
- Scientific Applications(Statistics, Data science, Machine Learning, etc)

### Installing Python3 Interpreter:
1. verify if you have installed in your pc, you only need to open the terminal, CMD, Powershell, etc.

On Windows:
```
C:\Users\agzso>python --version
Python 3.8.2

C:\Users\agzso>
```

On Linux version 2
```
root@vagrant-ubuntu-trusty-64:~# python --version
Python 2.7.6
root@vagrant-ubuntu-trusty-64:~#
```
or for version 3

```
root@vagrant-ubuntu-trusty-64:~# python3 --version
Python 3.8.2
root@vagrant-ubuntu-trusty-64:~#
```
Python 3.x is the current version and is under active development.
Python 2.x is the legacy version and will receive only security updates until 2020. No new features will be

implemented. Note that many projects still use Python 2, although migrating to Python 3 is getting easier.

...So, if the terminal displays  a python version as a 'Python 3.8.2' or 'Python 2.7.6', congrats you have Python Installed.

...But, if Not go to next Step:

2. Download and Install a Python Version(Python 3.8.2)

- Go to the Official [Website](https://www.python.org/).

On Windows : 

a. Only go to the official Website and download the current python version for your Windows 32 or 64 bits.

b. Install the Python, is simple only select Next in all step of installation process, but remember make sure to add python to the PATH.

c. To be sure, open the terminal and type again 'python --version'. and if shows the version, you python is OK intalled in your windows.

on Linux:

a. using a terminal only types the next commands:

- sudo apt-get update
```
root@vagrant-ubuntu-trusty-64:~# sudo apt-get update
Hit http://security.ubuntu.com trusty-security InRelease
Hit http://security.ubuntu.com trusty-security/main Sources
Hit http://security.ubuntu.com trusty-security/universe Sources
Hit http://security.ubuntu.com trusty-security/main amd64 Packages
Hit http://security.ubuntu.com trusty-security/universe amd64 Packages
Hit http://security.ubuntu.com trusty-security/main Translation-en
Hit http://security.ubuntu.com trusty-security/universe Translation-en
Get:1 http://repo.mysql.com trusty InRelease [33.3 kB]
```

- sudo apt-get install python3
```
root@vagrant-ubuntu-trusty-64:~# sudo apt-get install python3
Reading package lists... Done
Building dependency tree
Reading state information... Done
python3 is already the newest version.
The following packages were automatically installed and are no longer required:
  libcanberra-gtk3-0 libcanberra-gtk3-module libcanberra0 libfontenc1
  libllvm3.4 libnotify-bin libnotify4 libtdb1 libxaw7 libxfont1 libxkbfile1
  libxmu6 notification-daemon sound-theme-freedesktop x11-xkb-utils
  xfonts-base xfonts-encodings xfonts-utils xserver-common
Use 'apt-get autoremove' to remove them.
0 upgraded, 0 newly installed, 0 to remove and 7 not upgraded.
root@vagrant-ubuntu-trusty-64:~#
```

Optional: Recommended install pip(package installer for python), pip normally is already installed in python3 >= 3.4 or python2 >= 2.7








