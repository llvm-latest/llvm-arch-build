# LLVM Arch Build

This is a fork of the PKGBUILD configuration for building the LLVM compiler infrastructure on Arch Linux.

## Overview

LLVM is a collection of modular and reusable compiler and toolchain technologies. This project provides PKGBUILD configuration for building LLVM core components and runtime libraries on Arch Linux.

> __Note__: This is a forked version of the original Arch Linux LLVM package.  
> The original package can be found at the [Arch Linux Package Repository](https://gitlab.archlinux.org/archlinux/packaging/packages/llvm).

## Features

- __TODO:__ Optimizing build configuration

## Version Information

- LLVM Version: 21.1.6
- Architecture: x86_64

## Package Contents

This project builds the following two packages:

- __llvm__: Compiler infrastructure, including LLVM toolchain and utilities
- __llvm-libs__: LLVM runtime libraries, providing shared library support

## Build Instructions

1. Clone or download this repository
2. Navigate to the project directory
3. Run `makepkg` to build the packages
4. Use `pacman -U` to install the generated packages

Example:

```sh
git clone https://github.com/llvm-latest/llvm-arch-build
cd llvm-arch-build
makepkg -si
sudo pacman -U llvm-*.pkg.tar.zst
# or using yay
yay -U llvm-*.pkg.tar.zst
```

## Related Links

- [LLVM Official Website](https://llvm.org/)
- [LLVM GitHub Repository](https://github.com/llvm/llvm-project)
- [Arch Linux Package Repository](https://gitlab.archlinux.org/archlinux/packaging/packages/llvm)

## License

This project is licensed under Apache-2.0 WITH LLVM-exception. See the LICENSE file for details.
