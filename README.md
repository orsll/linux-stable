# `linux-stable`

This repository contains a [PKGBUILD](https://wiki.archlinux.org/title/PKGBUILD)
to build the latest stable version of the Linux [kernel](https://kernel.org/),
with which the package in the official Arch
[repositories](https://archlinux.org/packages/core/x86_64/linux/) is not always
up to date.  It uses the same build config as the official Arch package but does
not include all of the Arch-specific
[patches](https://github.com/archlinux/linux/releases/tag/v7.3.4-arch1).

> [!NOTE]
> The motivation behind this is to keep up with the latest Linux releases while
> I wait for hardware support updates for my new laptop.  There is probably no
> good reason to choose this over the official package unless you're in a
> similar situation.
