# Inphic S805 Teardown

Goes for ~~$15~~ (not anymore, you snooze you lose) $40 on [AliExpress](http://www.aliexpress.com/item/inphic-i5-S805-wifi-smart-tv-box-set-top-box-quad-core-1g-8g-android4-4/32504955757.html), has same SoC as the [Odroid C1](http://odroid.com/dokuwiki/doku.php?id=en:c1_hardware). Looks like a poor man's Odroid to me!

We bravely attempt to build and run mainline kernel on this little board. For that we join forces with the awesome [linux-meson](http://linux-meson.com/doku.php) project.

## Prerequisites

 - arm-linux-gnueabihf toolchain ([arm-linux-gnueabihf-gcc](https://aur.archlinux.org/packages/arm-linux-gnueabihf-gcc/) on AUR)
 - [Mainline kernel](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git) clone
 - [Buildroot](http://www.buildroot.org/)

