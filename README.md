# NerdFetch
 A POSIX Linux/macOS fetch script using Nerdfonts

<!-- ![Screenshot](https://i.imgur.com/and9kuQ.png) -->
![Screenshot](https://i.imgur.com/PPfnHqN.png)

### Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- bc (optional, but most systems already have this)
- Pretty much any Linux distro/macOS

### To install and run:

#### [Automatically (Arch Linux via the AUR)](https://aur.archlinux.org/packages/nerdfetch/):

```shell
yay -S nerdfetch
```



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

### Features:
- Package manager and package count detection across many OSes
- Support across all nerdfonts
- Uptime detection that is actually good
- Unlike neofetch, it uses almost no resources
- Portable
- POSIX compliant
- Tested on Pop!_OS, NixOS, Ubuntu, Alpine, Debian, macOS 10, Arch, Manjaro, Bedrock, Gentoo, Kiss, EndeavourOS, ArcoLinux, Solus, LilKirbsOS, and Android

### OSes fully supported:
- Debian/Ubuntu based Linux
- Arch based Linux
- RPM based Linux
- Fedora Linux
- openSUSE Linux
- Bedrock Linux
- Alpine Linux
- KISS Linux
- Void Linux
- Gentoo Linux
- Exherbo Linux
- Solus Linux

### OSes partially supported:
- macOS
- Android

### Known issues:
- Issues with uptime on Android
- No support for BSD package managers/uptime calculations.
- Weird spacing on macOS if you use brew given its complete weirdness
- In [Cool-Retro-Term](https://github.com/Swordfish90/cool-retro-term), the coffee icon shows up as a Chinese character. To fix this, simply change the default font to a NerdFont you installed, or change the existing coffee icon to `nf-fa-coffee` from the [NerdFonts cheet sheet](https://www.nerdfonts.com/cheat-sheet).
