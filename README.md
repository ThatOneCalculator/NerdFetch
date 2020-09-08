# CalcFetch
 A POSIX Linux/macOS fetch script using Nerdfonts

![Screenshot](https://i.imgur.com/tlZt1X8.png)

### Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- Pretty much any Linux distro/macOS

### To install and run:

Automatically: `curl https://0x0.st/i6y5.sh | sh`

Manually:
```shusr/bin/env bash
git clone https://github.com/ThatOneCalculator/CalcFetch.git
cd CalcFetch/
sudo chmod +x calcfetch
echo /bin/ ~/.local/bin/ | xargs -n 1 sudo cp calcfetch
cd ..
sudo rm -r CalcFetch/
calcfetch
```

### Features:
- Package manager and package count detection
- Support across all nerdfonts
- Uptime detection that is actually good
- Unlike neofetch, it uses almost no resources
- Portable
- POSIX compliant
- Tested on Pop!_OS, NixOS, Ubuntu, Alpine, Debian, macOS 10, Arch, Gentoo, Kiss, and Android

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
- Gentoo Linux*
- macOS 10.x

### Know issues:

- No support for BSD package managers/uptime calculations.
- *Some wonkiness on Gentoo
- Completely breaks on Android due to the fact that /etc/os_release doesn't exist on Android
- In [Cool-Retro-Term](https://github.com/Swordfish90/cool-retro-term), the coffee icon shows up as a Chinese character. To fix this, simply change the default font to a NerdFont you installed, or change the existing coffee icon to nf-fa-coffee from the [NerdFonts cheet sheet](https://www.nerdfonts.com/cheat-sheet).
