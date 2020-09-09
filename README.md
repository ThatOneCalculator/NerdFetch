# CalcFetch
 A POSIX Linux/macOS fetch script using Nerdfonts

![Screenshot](https://i.imgur.com/uYHWrvm.png)

### Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- Pretty much any Linux distro/macOS

### To install and run:

Copy-paste this into your terminal:
```sh
git clone https://github.com/ThatOneCalculator/CalcFetch.git
cd CalcFetch/
sudo install -m755 calcfetch /bin/calcfetch
cd ..
sudo rm -r CalcFetch/
calcfetch
```

### Features:
- Package manager and package count detection across many OSes
- Support across all nerdfonts
- Uptime detection that is actually good
- Unlike neofetch, it uses almost no resources
- Portable
- POSIX compliant
- Tested on Pop!_OS, NixOS, Ubuntu, Alpine, Debian, macOS 10, Arch, Manjaro, Bedrock, Gentoo, Kiss, EndeavorOS, and Android

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
- macOS 10.x

### Know issues:

- No support for BSD package managers/uptime calculations.
- Completely breaks on Android due to the fact that /etc/os_release doesn't exist on Android
- In [Cool-Retro-Term](https://github.com/Swordfish90/cool-retro-term), the coffee icon shows up as a Chinese character. To fix this, simply change the default font to a NerdFont you installed, or change the existing coffee icon to nf-fa-coffee from the [NerdFonts cheet sheet](https://www.nerdfonts.com/cheat-sheet).
