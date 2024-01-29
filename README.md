# KernelSU Builder

KernelSU Builder is a tool that allows you to build kernels with KernelSU support or without it.

[![Build Status](https://app.travis-ci.com/HowWof/KernelSU_Builder_Nashc.svg?token=YpCmyKiASUZZvuKpAUfa&branch=master)]()

## Table of Contents
- [Getting Started](#getting-started)
- [Adding a Device](#adding-a-device)
- [Flashing the Kernel](#flashing-the-kernel)

## Getting Started

Follow these steps to use this Builder:

1. Fork this repository.
2. Create an account on Travis CI.
3. Add your forked repository to Travis CI.
4. Update the `sources.yml` file with your build requirements and the `.travis.yml` file with your variables.
5. Wait for the build to finish.

## Adding a Device

1. Fork the AnyKernel repository and adapt it to your device.
2. Edit the `.travis.yml` file to clone your forked AnyKernel repository.

## Flashing the Kernel

To flash the kernel onto your device:

1. Download the kernel release from GitHub.
2. Use your preferred recovery tool to flash the kernel.
3. If you want root access, flash Magisk or KernelSU.
4. Reboot your device.