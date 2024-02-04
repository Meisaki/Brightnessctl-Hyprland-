# Brightnessctl For Hyprland 
Just Giving a Overview for New user 
A shell script for controlling screen brightness its minimal also easy to use

I was finding a Brightness control tool  as minimal and wayland-based not x11 its should be easy to use so i get two.
Brillo and Brightnessctl where brillo somehow older then brightnessctl which is why i go for Brightnessctl (if you have other tool 
you can  ask as answer) 
 
## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)
- [License](#license)

## Features
- its minimal and easy to use
- it is latest from brightness pakages (brillo is not latest)
- Read the repo for more information

## Installation

### By Arch Repo
```
sudo pacman -S brightnessctl
```
### By Source
 - cloning Repo
```
git clone https://github.com/Hummer12007/brightnessctl.git
```
 - Building and Installing (Stick with Folder)
```
./configure && make install
```
 - Help (Need for valid arguments)
```
./configure --help
```
### Check version
```
brightnessctl V
```
## Usage 
### Options
- `-l, --list`			list devices with available brightness controls.
- `-q, --quiet`			suppress output.
- `-p, --pretend`			do not perform write operations.
- `-m, --machine-readable`	produce machine-readable output.
- `-n, --min-value`		set minimum brightness, defaults to 1.
- `-e, --exponent[=K]`		changes percentage curve to exponential.
- `-s, --save`			save previous state in a temporary file.
- `-r, --restore`			restore previous saved state.
- `-h, --help`			print this help.
- `-d, --device=DEVICE`		specify device name (can be a wildcard).
- `-c, --class=CLASS`		specify device class.
- `-V, --version`			print version and exit.
### Functions
 - `i, info`			get device info.
 - `g, get`			get current brightness of the device.
 - `m, max`			get maximum brightness of the device.
 - `s, set VALUE`			set brightness of the device.
### Value (Parameter)
 -  specific value
    -  Example: 500
 - percentage value
   - Example: 50%
 - specific delta
   - Example: 50- or +10
 - percentage delta
   - Example: 50%- or +10%
## Troubleshooting
- Its outdated for sure because in page its last release 2018 but brillo also older then that.
- Arch Package last update was in 2023 which gives some liablity as brillo Arch package is older then that also
- Above two point show that some people can run in into problem if you run in into some T_ask me
## License
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)



