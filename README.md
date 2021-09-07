# Ubuntu Frame

## Description

The foundation for many embedded graphical display implementations. `ubuntu-frame` is a simple fullscreen shell (based on Wayland) used for kiosks, industrial displays, digital signage, smart mirrors, etc.

The application you choose (or provide) gets a fullscreen window (or windows) and input from touch, keyboard and mouse without needing to deal with the specific hardware.

## Configuration

There are three snap configuration options:

* `daemon=[true|false]` enables the daemon (defaults to false on classic systems)
* `config=<options for the shell>`
* `display=<options for display layout>`

The configuration options are described in detail in [REFERENCE.md](REFERENCE.md)

## Development

Developers working with Ubuntu Frame may find the following useful:

* [RUNNING_ON_YOUR_DESKTOP.md](RUNNING_ON_YOUR_DESKTOP.md)
* [RUNNING_IN_A_VM.md](RUNNING_IN_A_VM.md)
* [RUNNING_ON_YOUR_DEVICE.md](RUNNING_ON_YOUR_DEVICE.md)

----
[![ubuntu-frame](https://snapcraft.io/ubuntu-frame/badge.svg)](https://snapcraft.io/ubuntu-frame)