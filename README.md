# MarkedRain Kernel Modules

This repository contains out-of-tree Linux kernel modules for use with the **MarkedRain** operating system. These modules are built specifically for **Linux kernel version 6.11.0**.

## Purpose

Kernel modules are essential for extending the functionality of the Linux kernel without recompiling it. This repository provides:

- Drivers for specific hardware
- Filesystem support
- Network protocol modules
- Any other kernel features required by MarkedRain

## How it works

This repository is automatically cloned by **MarkedRain Linux**'s Makefile to include necessary kernel modules during system build.
The parameter `--depth 1` is added into the clone command to clone the most recent version of this repository.

## Target Kernel

- **Version:** `6.11.0`
- Ensure your running kernel matches this version exactly to avoid compatibility issues.

---

**Maintained by:** [MarkedRain Linux](https://github.com/MarkedRain)
