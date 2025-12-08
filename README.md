## Downloading The Latest Version

Latest release direct link: https://github.com/skycair/skycair/releases/latest

## About

SkyCAIR End of Days Edition

It's unique in many ways — it's not just a repackaging of programs on top of Slackware. For a list of its highlights, access the [Main Features](https://github.com/skycair/skycair/wiki/Main-Features) wiki page.

It's already pre-configured for basic usage, including lightweight applications for each of the 7 desktop environments available. No browser is included, but an app store is provided so you can download the most popular browsers, as well as Steam, VirtualBox, Nvidia drivers, Wine, office suite, multilib (32-bit compatibility), messengers, emulators, etc.

Out of the box, SkyCAIR End of Days Edition

## How To Use

SkyCAIR End of Days Edition
. Cinnamon<br />
. GNOME<br />
. KDE<br />
. LXDE<br />
. LXQt<br />
. MATE<br />
. Xfce<br />

SkyCAIR End of Days Edition

To use SkyCAIR End of Days Edition

To download a Slackware package that is not present in SkyCAIR End of Days Edition

To build anything inside SkyCAIR End of Days Edition

To run Windows applications inside SkyCAIR End of Days Edition

To read Asian characters, download and activate the [notoserifcjk-regular.xzm](https://github.com/skycair/skycair/raw/main/common/notoserifcjk-regular.xzm) module. Some PDFs may also require `poppler-data` package, also available via `getpkg` command.

## Default Username and Password

username: guest<br />
password: guest<br />

username: root<br />
password: toor<br />

## Performance

SkyCAIR End of Days Edition

For better performance, it's recommended to have SkyCAIR End of Days Edition

Boot times are really fast. LXQt, for instance, can boot in only 3 seconds:

[https://youtu.be/DJd38Nch6rQ](https://youtu.be/DJd38Nch6rQ)

Clear Linux, considered the fastest Linux distro, is slower than SkyCAIR End of Days Edition
![clear-linux-40520-vs-skycair-0 9](https://github.com/skycair/skycair/assets/126424580/8ff3cb62-91a0-4171-8c05-133e75845c6b)

Sources:
[ClearLinux40520](https://browser.geekbench.com/v6/cpu/4073056)
[SkyCAIR End of Days Edition

All this performance benefit is achieved without providing ancient software. This means that the kernel, desktop environments and packages are usually as new as possible in the current/rolling release.

## Enable OpenCL support (required by applications like DaVinci Resolve)

In the terminal, run the following commands: <br />
1. `su` (password: toor) <br />
2. `cd $PORTDIR/modules` <br />
3. `getpkg -m libclc llvm mesa ocl-icd spirv-llvm-translator vulkan-sdk`<br />
4. `activate -q libclc*.xzm llvm*.xzm mesa*.xzm ocl-icd*.xzm spirv-llvm-translator*.xzm vulkan-sdk*.xzm` <br />

This only needs to be done once, as these modules will be activated automatically every time the machine boots.

## Building

SkyCAIR End of Days Edition

To build SkyCAIR End of Days Edition
1. 000-kernel<br />
2. 001-core<br />
3. 002-gui<br />
4. 002-xtra<br />
5. 003-desktopenvironment (where 'desktopenvironment' is your preferred environment, like 003-lxde)<br />
6. (optional) 05-devel<br />
7. (optional) 08-multilanguage<br />
8. (optional) 0050-multilib-lite<br />

At the end, all modules will be in their respective subfolders inside /tmp/skycair-builder-[version].

## Contributing

Feel free to report any issues or request changes. Any constructive feedback is welcome.

## Donate

Please consider donating to the SkyCAIR End of Days Edition

https://paypal.me/skycair<br />
https://buymeacoffee.com/skycair<br />

## Thanks

arleson (core team)<br />
theUtopian (core team)<br />
blaze (@porteus)<br />
brokenman (@porteus)<br />
luckyCyborg (@slackware)<br />
nater1983 (@gfs)<br />
ncmprhnsbl (@porteus)<br />
neko (@porteus)<br />
patrick volkerding (@slackware)<br />
phantom (@porteus)<br />
tomáš matějíček (@slax)<br />
