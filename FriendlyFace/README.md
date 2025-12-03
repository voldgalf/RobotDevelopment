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


Below is the command for installing all necessary packages for FriendlyFace

```bash
sudo apt-get install libsdl3-dev & sudo apt install build-essential cmake
```

The necessary packages include:

- SDL
- CMake
