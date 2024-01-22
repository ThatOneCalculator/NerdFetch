# NerdFetch
 A POSIX \*nix (Linux, macOS, Android, BSD, etc) fetch script using Nerdfonts (and others)

*Nerdfont*

![Screenshot](https://github.com/ThatOneCalculator/NerdFetch/assets/44733677/37ea2a01-80e1-457b-b922-89cc708c527e)

*Phosphor Bold*

![Phosphor](https://github.com/ThatOneCalculator/NerdFetch/assets/44733677/07d2cc29-5a58-4a00-8a52-95ec2032988b)

*Cozette*

![Cozette](https://github.com/ThatOneCalculator/NerdFetch/assets/44733677/574e8417-adee-45cd-9a4e-68661240f458)

### Dependencies

- [Any Nerdfonts font](https://www.nerdfonts.com/font-downloads), [Cozette](https://github.com/slavfox/Cozette), or [Phosphor](https://github.com/phosphor-icons/homepage/releases/tag/v2.0.0)
- POSIX-compliant shell
- `which`
- Anything but Windows

### To install and run

[![Packaging status](https://repology.org/badge/vertical-allrepos/nerdfetch.svg)](https://repology.org/project/nerdfetch/versions)

#### How to switch fonts

- Nerdfonts is used by default
- Use `-c` for Cozette
- Use `-p` for Phosphor

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
nerdfetch
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

### OSes tested

- Debian based Linux
- Ubuntu based Linux
- Arch based Linux
- Gentoo based Linux
- RedHat based Linux
- OpenSUSE based Linux
- Bedrock Linux
- Alpine Linux
- KISS Linux
- Void Linux
- Exherbo Linux
- NixOS Linux
- Solus Linux
- yiffOS Linux
- Slackware Linux
- macOS
- FreeBSD
- OpenBSD
- Android
- NetBSD\*

### Known issue(s)

- `nsh` is currently unsupported (https://github.com/ThatOneCalculator/NerdFetch/issues/46)
- \*NetBSD currently doesn't show memory usage or packages installed (https://github.com/ThatOneCalculator/NerdFetch/issues/39)
