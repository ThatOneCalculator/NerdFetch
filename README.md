# NerdFetch: Cozette Edition
 A POSIX \*nix (Linux, macOS, \*BSD, etc) fetch script using Nerdfonts. Cozette edition.

![Screenshot](https://media.discordapp.net/attachments/810799100940255260/859694086374293515/unknown.png)

### Dependencies:

- [Cozette](https://github.com/slavfox/Cozette)
- bc (optional, but most systems already have this)
- Pretty much any Linux distro/macOS

### To install and run:

#### [Automatically (Arch Linux via the AUR)](https://aur.archlinux.org/packages/nerdfetch-cozette/):

```shell
yay -S nerdfetch-cozette
```
Make sure to replace `yay` with whatever AUR helper you use. 

#### Manually:

Copy-paste this into your terminal:

```sh
# clone and go into repo
git clone https://github.com/ThatOneCalculator/NerdFetch.git
cd NerdFetch/
# change branch to the cozette version
git checkout cozette
# install
sudo install -m755 nerdfetch /usr/bin/nerdfetch
# go back and remove the download
cd ..
rm -rf NerdFetch/
# run
nerdfetch
```

#### Run once (curl):

Note that this will not install the program.
```sh
curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/cozette/nerdfetch | sh
```

### Features:
- Package manager and package count detection across many OSes
- Uptime detection that is actually good
- Unlike neofetch, it uses almost no resources
- Portable
- POSIX compliant
- Tested on Pop!\_OS, NixOS, Ubuntu, PeppermintOS, Alpine, Debian, macOS 10, Arch, Manjaro, Bedrock, Gentoo, Kiss, EndeavourOS, ArcoLinux, Solus, Exherbo, LilKirbsOS, Fedora, Slackware, and Android

### OSes fully supported:
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
- Solus Linux
- Slackware Linux*
- macOS 10.x
- macOS 11

### OSes partially supported:
- Android
- \*BSD

### Known issues:
- Issues with uptime on Android
- No support for BSD package managers/uptime calculations.
- \*In Slackware Linux, make sure to have /usr/sbin in PATH

