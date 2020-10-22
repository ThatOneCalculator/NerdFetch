# NerdFetch
 A POSIX Linux/macOS fetch script using Nerdfonts

![Screenshot](https://i.imgur.com/58uSut6.png)

### Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- bc (optional, but most systems already have this)
- Pretty much any Linux distro/macOS

### To install and run:

Copy-paste this into your terminal:

```sh
# clone and go into repo
git clone https://github.com/Ohio2/NerdFetch.git
cd NerdFetch/
# install 
sudo scp nerdfetch /usr/local/bin/nerdfetch-ohio2
# go back and remove the download
cd ..
rm -rf NerdFetch/
# run
nerdfetch-ohio2
```
##Updating:
```
#remove nerdfetch-ohio2
sudo rm /usr/bin/nerdfetch-ohio2
#Follow To install and run.
```
## Features:
- Package manager and package count detection across many OSes
- Support across all nerdfonts
- Uptime detection that is actually good
- Unlike neofetch, it uses almost no resources
- Portable
- POSIX compliant
- Tested on Pop!_OS, NixOS, Ubuntu, Alpine, Debian, macOS 10, Arch, Manjaro, Bedrock, Gentoo, Kiss, EndeavourOS, ArcoLinux, Solus, LilKirbsOS, and Android

### OSes supported:
- Ubuntu based Linux (Debi script)
- Arch based Linux (normal script)
- Other (Pengoo script)
(Logos)


### Known issues:

- No support for BSD package managers/uptime calculations.
- Completely breaks on Android due to the fact that /etc/os_release doesn't exist on Android
- Weird spacing on macOS if you use brew given its complete weirdness
- In [Cool-Retro-Term](https://github.com/Swordfish90/cool-retro-term), the coffee icon shows up as a Chinese character. To fix this, simply change the default font to a NerdFont you installed, or change the existing coffee icon to `nf-fa-coffee` from the [NerdFonts cheet sheet](https://www.nerdfonts.com/cheat-sheet).
