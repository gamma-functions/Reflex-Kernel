# Reflex Kernel

**An operating system kernel that is nothing special, written in C and a little assembly language.**

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Code Size](https://img.shields.io/badge/code%20size-~%20XX%20KB-blue)]()
![Written in](https://img.shields.io/badge/written%20in-C%20&%20ASM-9cf)

## What did it do? (Only a little at present, and it will be done in the future)

*   Start up and then run from real mode to protected mode.
*   It can print `Hello, World!` via the serial port (`COM1`). Just used the `printk` function, nothing magical.
*   That's all. Really.

## Why is it called "Reflex"?

It means "reflection". Thinking that the most fundamental job of the kernel is to respond to various interrupts and requests, just like neural reflexes, I casually gave it this name. It's much more ordinary than those named after constellations or myths.

## How to build? (If you really want to try)

**Warning: This project is very ordinary and may not be worth your time.**

1.  You need a Linux environment that can compile `C` and assembly. (I did it in WSL)
2.  Need common tools such as `gcc`, `nasm`, `ld`, `qemu`.
3.  Clone the project, then `make all`.
4.  Run with `make qemu`. You should see the same `Hello, World!` message in the QEMU console and the `tmux` split-screen serial port.

Just these few steps, nothing complicated.
## Future Plans? (Probably won't do)

Just some features that ordinary kernels have, I might code them for fun, or might not have time:

- [ ] Interrupt Descriptor Table (IDT)
- [ ] Physical Memory Management
- [ ] Virtual Memory (Paging)
- [ ] Multitasking
- [ ] User Mode
- [ ] Simple File System
- [ ] A responsive shell

(Too much homework, might dig the pit very slowly)

## About Me

An ordinary junior high school student. Write some code on weekends and holidays as relaxation. There might be many problems in the code, after all, still learning.

## License

MIT License. It's just the most ordinary open source license, take it if you want to use it, no need to tell me.

---

**Last time saying, this project is very ordinary, just something I do for fun myself.**
