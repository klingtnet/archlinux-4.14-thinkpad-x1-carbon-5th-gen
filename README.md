# Linux 4.14 for Lenovo X1 Carbon 5th Gen with Touchpad Patch

This is a fork of https://aur.archlinux.org/pkgbase/linux-tp-x1-carbon-5th/ which does not get updated anymore.
Unfortunately, the Elantech touchpad is still not supported in the latest kernel (4.14), thus a small patch has still to be applied.

## Installation

If you have the build-essentials installed then you can install the kernel besides stable (or any other kernel you use) like this:

```sh
$ sudo makepkg -i
```

## Issues

- there are no compatible DKMS modules for virtualbox at the moment
- I haven't updated the kernel config file so you get asked about some new config options, normally you can use the default answer for everything
