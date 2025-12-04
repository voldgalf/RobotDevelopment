# FriendlyFace

### Overview

A simple customizable robot face written in C with SDL.

> [!WARNING]
> FriendlyFace is designed for monitor use via HDMI, **not** embedded screens.

#### Features

- Customizable faces
- Emotional controlled expressions
  
#### Emotional Face Controls protocol

The protocol allows for emotion controlled facial expressions, via socket connections with an *emotion server*

The Emotional Face Controls protocol is seperate from the main thread, running in a second thread.

This is completely optional and is **not** required for the program to run correctly.

### Installation

> [!CAUTION]
> FriendlyFace is currently only supported on Linux

Follow the commands below to install the necessary packages before building

```bash
# Update apt before continuing
sudo apt update

# FriendlyFace requires SDl3, to install it run:
sudo apt-get install libsdl3-dev

# Building FriendlyFace requires CMake, to install it run:
sudo apt install build-essential cmake
```
