---
title: Firmware
parent: Generation 3
has_children: true
has_toc: false
nav_order: 4
---

# Firmware (modified)

This repository contains a modified version of panels firmware with makefile for building/programming from the command line.

Requirements: gcc-avr, binutils-avr, gdb-avr avr-libc avrdude

On ubuntu:

```bash
sudo apt-get install gcc-avr binutils-avr gdb-avr avr-libc avrdude
```

## Build/Program

```sh
make hex    # compile hex file
make flash  # install hex file
```
