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
- Anything but Windows

### To install and run

[![Packaging status](https://repology.org/badge/vertical-allrepos/nerdfetch.svg)](https://repology.org/project/nerdfetch/versions)

#### How to switch fonts

- Nerdfonts is used by default
- Use `-c` for Cozette
- Use `-p` for Phosphor
- Use `-e` for Emojis

#### [Arch Linux (AUR)](https://aur.archlinux.org/packages/nerdfetch/)

```sh
yay -S nerdfetch # -git
nerdfetch
```
Make sure to replace `yay` with whatever AUR helper you use.

#### [macOS (homebrew)](https://formulae.brew.sh/formula/nerdfetch)

```sh
brew install nerdfetch
nerdfetch
```

#### [Nix](https://search.nixos.org/packages?show=nerdfetch)

```sh
nix-shell -p nerdfetch
nerdfetch
``` 

#### [Gentoo (GURU)](https://gpo.zugaina.org/Overlays/guru/app-misc/nerdfetch)/[LiGurOS](https://gitlab.com/liguros/liguros-repo/-/tree/stable/app-misc/nerdfetch)

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

#### [BirbOS](https://github.com/birb-linux/BirbOS-packages/tree/dev/nerdfetch)

```sh
sudo birb nerdfetch
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
- BirbOS Linux
- macOS
- Android
- FreeBSD
- OpenBSD
- NetBSD
- OpenWrt

### Known issue(s)

- `nsh` is currently unsupported (https://github.com/ThatOneCalculator/NerdFetch/issues/46)
