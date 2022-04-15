# zola-debian

This repository contains the source to build a Debian package for [zola](https://github.com/getzola/zola).

## Changes [from original](https://github.com/barnumbirr/zola-debian)
- Changed target for ARM devices, namely `armv7`
- Added caching to GitHub action to speed up builds drastically (hopefully)
- Add missing build dependencies (`pkg-config`)

## Usage
0. [Download the latest .deb from the releases page](https://github.com/LLEB-ME/zola-debian/releases/latest)
1. Use `dpkg` to install the .deb (`sudo dpkg -i zola-*.deb`)
2. ???
3. Profit.
