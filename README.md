# CalcFetch
 A POSIX Linux/macOS fetch script using Nerdfonts

![Screenshot](https://i.imgur.com/uYHWrvm.png)

### Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- Pretty much any Linux distro/macOS

### To install and run:

Copy-paste this into your terminal:
```sh
# clone repo
git clone https://github.com/ThatOneCalculator/CalcFetch.git
# cd and install
cd CalcFetch/
sudo install -m755 calcfetch /bin/calcfetch
# go back and remove the download
cd ..
sudo rm -r CalcFetch/
# run
calcfetch
```

### Features:
- Package manager and package count detection across many OSes
- Support across all nerdfonts
- Uptime detection that is actually good
- Unlike neofetch, it uses almost no resources
- Portable
- POSIX compliant
- Tested on Pop!_OS, NixOS, Ubuntu, Alpine, Debian, macOS 10, Arch, Manjaro, Bedrock, Gentoo, Kiss, EndeavorOS, Solus, and Android

### OSes supported:
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
- Solus Linux
- macOS 10.x

### Know issues:

- No support for BSD package managers/uptime calculations.
- Completely breaks on Android due to the fact that /etc/os_release doesn't exist on Android
- Weird spacing on macOS if you use brew given its complete weirdness
- In [Cool-Retro-Term](https://github.com/Swordfish90/cool-retro-term), the coffee icon shows up as a Chinese character. To fix this, simply change the default font to a NerdFont you installed, or change the existing coffee icon to nf-fa-coffee from the [NerdFonts cheet sheet](https://www.nerdfonts.com/cheat-sheet).
