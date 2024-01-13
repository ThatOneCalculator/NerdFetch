# NerdFetch
 A POSIX \*nix (Linux, macOS, Android, BSD, etc) fetch script using Nerdfonts

![Screenshot](https://github.com/ThatOneCalculator/NerdFetch/assets/44733677/0bc8872f-70b0-485f-a5f5-cc45bb2dac79)

### Dependencies

- [Any Nerdfonts font](https://www.nerdfonts.com/font-downloads)
- POSIX-compliant shell
- Anything but Windows

### To install and run

[![Packaging status](https://repology.org/badge/vertical-allrepos/nerdfetch.svg)](https://repology.org/project/nerdfetch/versions)

#### [Arch Linux](https://aur.archlinux.org/packages/nerdfetch/):

```sh
yay -S nerdfetch
nerdfetch
```

Make sure to replace `yay` with whatever AUR helper you use.

#### [Gentoo](https://gpo.zugaina.org/Overlays/guru/app-misc/nerdfetch)/[LiGurOS](https://gitlab.com/liguros/liguros-repo/-/tree/stable/app-misc/nerdfetch)

Add the GURU overlay: <https://wiki.gentoo.org/wiki/Project:GURU/Information_for_End_Users> (*Not needed for LiGurOS*)

```sh
emerge nerdfetch
```

#### [yiffOS](https://packages.yiffos.gay/nerdfetch)

```sh
bulge install nerdfetch
nerdfetch
```

#### Manually

Copy-paste this into your terminal:

```sh
sudo curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/main/nerdfetch -o /usr/bin/nerdfetch
sudo chmod +x /usr/bin/nerdfetch
nerdfetch
```

#### Android with Termux

Copy-paste this into Termux:

```sh
curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/main/nerdfetch -o /data/data/com.termux/files/usr/bin/nerdfetch
chmod a+x /data/data/com.termux/files/usr/bin/nerdfetch
nerdfetch
```

#### Run once

Note that this will ***not*** install the program.

```sh
curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/main/nerdfetch | sh
```

### Features

- Strong cross-OS compatability
- Not bloated
- Portable
- POSIX

### POSIX-compliant shells tested

- bash ✅
- zsh ✅
- ksh ✅
- dash ✅
- yash ✅
- oil (osh)\* ⚠️
- nsh ❌ (see https://github.com/ThatOneCalculator/NerdFetch/issues/46)

### OSes tested

- Debian based Linux
- Ubuntu based Linux
- Arch based Linux
- RedHat based Linux
- SUSE based Linux
- Bedrock Linux
- Alpine Linux
- KISS Linux
- Void Linux
- Gentoo Linux
- Exherbo Linux
- NixOS Linux
- Solus Linux
- yiffOS Linux
- Slackware Linux
- macOS
- FreeBSD
- OpenBSD
- Android

### Known issue(s)

- \* With oil, a warning `getprop: not found` is thrown
- NetBSD is currently unsupported (https://github.com/ThatOneCalculator/NerdFetch/issues/39)