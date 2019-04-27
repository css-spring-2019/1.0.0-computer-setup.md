## Setup your development environment

Some of the following tools require the use of the terminal (Terminal.app). This can be quite overwhelming if you've never used it before, but don't worry, you'll soon grow comfortable with it.

The easiest way to open an application is to search for it via Spotlight. The default keyboard shortcut for invoking Spotlight is command-Space. Once Spotlight is up, just start typing the first few letters of the app you are looking for, and once it appears, select it, and press return to launch it.

## Homebrew and Xcode

This guide assumes you are on a Mac and will be using homebrew.

Install xcode package:

```
$ xcode-select --install
```

Click through all confirmation commands.

Install homebrew:

```
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew doctor
```

## Python Versions with Homebrew

You can manage python versions with Homebrew. 

Install Python3:

```
$ brew update
$ brew install python3
```

Verify python3:

```
$ python3 --version
Python 3.6.X
```

Verify python 2.7 still works:

```
$ python
Python 2.7.X (default, Dec 18 2016, 07:03:39)
[GCC 4.2.1 Compatible Apple LLVM 8.0.0 (clang-800.0.42.1)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
```

## Pipenv

The `pipenv` program is designed to combine pip and virtualenv into one program. It has become the official Python-recommended resource for managing package dependencies.

Install pipenv for python3:

```
$ pip3 install -U pipenv
$ echo -e 'eval "$(pipenv --completion)"' >> ~/.profile
$ source ~/.profile
```

Install pipenv for Python2.7 **(optional)**:

```
$ pip install -U pipenv
```

### Apps

1. Chrome
2. Slack
3. Pycharm
4. Github account

### Creating an SSH key

You'll need an SSH key when using Github. SSH keys are a way to identify trusted computers, without involving passwords. Walk through the steps in the following tutorial to create your SSH key and add it to your Github account. Read the instructions completely, don't skim or skip. *Make sure to read the instructions carefully, the tutorial tells you everything you need to do.* [https://help.github.com/articles/generating-ssh-keys](https://help.github.com/articles/generating-ssh-keys)
