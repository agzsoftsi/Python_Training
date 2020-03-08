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
```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py
```

- and PEP8 (Python Enhancement Proposal) is a style guide for python code

You can install, upgrade, uninstall pep8.py with these commands:
```
$ pip install pep8
$ pip install --upgrade pep8
$ pip uninstall pep8
```
Current version is pep8 1.7.1


## day 002 - [Python Basics](Whiteboard_notes_Day2.jpg)

Create My Firt Script in Python Using Interavtive and non-interactive Mode

In Python, there are two options/methods for running code:

Interactive Mode

## Interactive mode, also known as the REPL provides us with a quick way of running blocks or a single line of Python code. The code executes via the Python shell, which comes with Python installation. Interactive mode is handy when you just want to execute basic Python commands or you are new to Python programming and just want to get your hands dirty with this beautiful language.

To access the Python shell, open the terminal of your operating system and then type "python". Press the enter key and the Python shell will appear. This is the same Python executable you use to execute scripts, which comes installed by default on Mac and Unix-based operating systems.

The >>> indicates that the Python shell is ready to execute and send your commands to the Python interpreter. The result is immediately displayed on the Python shell as soon as the Python interpreter interprets the command.

To run your Python statements, just type them and hit the enter key. You will get the results immediately, unlike in script mode. For example, to print the text "Hello World", we can type the following:
```
>>> print("Hello World")
Hello World
>>>
```
Here are other examples:
```
>>> 10
10
>>> print(5 * 20)
100
>>> "hi" * 5
'hihihihihi'
>>>
```
We can also run multiple statements on the Python shell. A good example of this is when we need to declare many variables and access them later. This is demonstrated below:
```
>>> name = "Nicholas"
>>> age = 26
>>> course = "Computer Science"
>>> print("My name is " + name + ", aged " + str(age) + ", taking " + course)
```
Output

My name is Nicholas, aged 26, taking Computer Science
Using the method demonstrated above, you can run multiple Python statements without having to create and save a script. You can also copy your code from another source then paste it on the Python shell.

Consider the following example:
```
>>> if 5 > 10:
...     print("5 is greater than 10")
... else:
...     print("5 is less than 10")
...
5 is less than 10
>>>
```
## Pros and Cons of Interactive Mode
The following are the advantages of running your code in interactive mode:

- Helpful when your script is extremely short and you want immediate results.
- Faster as you only have to type a command and then press the enter key to get the results.
- Good for beginners who need to understand Python basics.

The following are the disadvantages of running your code in the interactive mode:

- Editing the code in interactive mode is hard as you have to move back to the previous commands or else you have to rewrite the whole command again.
- It's very tedious to run long pieces of code.
- Next, we will be discussing the script mode.


## Script Mode
If you need to write a long piece of Python code or your Python script spans multiple files, interactive mode is not recommended. Script mode is the way to go in such cases. In script mode, You write your code in a text file then save it with a .py extension which stands for "Python". Note that you can use any text editor for this, including Sublime, Atom, notepad++, etc.

If you are in the standard Python shell, you can click "File" then choose "New" or simply hit "Ctrl + N" on your keyboard to open a blank script in which you can write your code. You can then press "Ctrl + S" to save it.

After writing your code, you can run it by clicking "Run" then "Run Module" or simply press F5.

Let us create a new file from the Python shell and give it the name "hello.py". We need to run the "Hello World" program. Add the following code to the file:
```
print("Hello World")
```
Click "Run" then choose "Run Module". This will run the program:


ther than executing the program from the graphical user interface, we can do it from the terminal of the operating system. However, you must be aware of the path to the directory where you have saved the file.

Open the terminal of your operating system then navigate to the location of the file. Of course, you will use the "cd (change directory)" command for this.

Once you reach the directory with the file, you will need to invoke the Python interpreter on the file. This can be done using the following syntax:
```
> python <filename>
```
To run the Python file from the terminal, you just have to type the python keyword followed by the name of the file. In our case, we need to run a file named "hello.py". We need to type the following on the terminal of the operating system:
```
> python hello.py
Hello World
```
If you want to get to the Python shell after getting the output, add the -i option to the command. This is demonstrated below:
```
> hello -i hello.py
Hello World
```

## Pros and Cons of Script Mode
The following are the advantages of running your code in script mode:

- It is easy to run large pieces of code.
- Editing your script is easier in script mode.
- Good for both beginners and experts.

The following are the disadvantages of using the script mode:

- Can be tedious when you need to run only a single or a few lines of cod.
- You must create and save a file before executing your code.
- Key Differences Between Interactive and Script Mode

Here are the key differences between programming in interactive mode and 
programming in script mode:

- In script mode, a file must be created and saved before executing the code to get results. In interactive mode, the result is returned immediately after pressing the enter key.
- In script mode, you are provided with a direct way of editing your code. - This is not possible in interactive mode.

## Conclusion
There are two modes through which we can create and run Python scripts: interactive mode and script mode. The interactive mode involves running your codes directly on the Python shell which can be accessed from the terminal of the operating system. In the script mode, you have to create a file, give it a name with a .py the extension then runs your code. The interactive mode is suitable when running a few lines of code. The script mode is recommended when you need to create large applications.