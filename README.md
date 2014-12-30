# Matrix Upgrades script

## Motivation

This is a script I made for the package upgrade process in Fedora, based in
[one of my favorite Matrix scenes](https://www.youtube.com/watch?v=7UHg3BZZcVw).

## Requirements

This script uses the Tkinter library for Python, so:

```shell
$ sudo yum install tkinter
```

## Usage

### Basic usage

```shell
$ ./upgrades
```

### As part of the user's bin folder

You can git clone this repo inside your $HOME/bin folder, and make a symlink
from $HOME/bin so you can execute the script like this:

```shell
$ upgrades
```

### Advanced Usage

You can exclude kernel updates using the -k modifier:

```shell
$ upgrades -k
```

## Extra info

"UPGRADES" image taken from "Matrix Reloaded", © 2003 Warner Bros.. All
Rights Reserved.
