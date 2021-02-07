# NerdFetch
 A POSIX \*nix (Linux, macOS, \*BSD, etc) fetch script using Nerdfonts

<!-- ![Screenshot](https://i.imgur.com/and9kuQ.png) -->
![Screenshot](https://linus-tech.tips/FKgAm_6Y7v.png)

[![Discord](https://discordapp.com/api/guilds/733856096963526667/embed.png?style=shield)](https://discord.gg/mG94DqX) 

### Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- bc (optional, but most systems already have this)
- Pretty much any Linux distro/macOS

### To install and run:

#### [Automatically (Arch Linux via the AUR)](https://aur.archlinux.org/packages/nerdfetch/):

```shell
yay -S nerdfetch
```
Make sure to replace `yay` with whatever AUR helper you use. 

#### Manually:

Copy-paste this into your terminal:

```sh
# clone and go into repo
git clone https://github.com/ThatOneCalculator/NerdFetch.git
cd NerdFetch/
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
curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/master/nerdfetch | sh
```

### Features:
- Package manager and package count detection across many OSes
- Support across all nerdfonts
- Uptime detection that is actually good
- Unlike neofetch, it uses almost no resources
- Portable
- POSIX compliant
- Tested on Pop!\_OS, NixOS, Ubuntu, Alpine, Debian, macOS 10, Arch, Manjaro, Bedrock, Gentoo, Kiss, EndeavourOS, ArcoLinux, Solus, Exherbo, LilKirbsOS, Fedora, Slackware, and Android

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
- In [Cool-Retro-Term](https://github.com/Swordfish90/cool-retro-term), the coffee icon shows up as a Chinese character. To fix this, simply change the default font to a NerdFont you installed, or change the existing coffee icon to `nf-fa-coffee` from the [NerdFonts cheet sheet](https://www.nerdfonts.com/cheat-sheet).
- \*In Slackware Linux, make sure to have /usr/sbin in PATH

