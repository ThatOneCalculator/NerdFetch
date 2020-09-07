# CalcFetch
 A POSIX Linux/macOS fetch script using Nerdfonts

![Screenshot](https://i.imgur.com/tlZt1X8.png)

Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- Bash
- Pretty much any Linux distro/macOS

To install and run:

```shusr/bin/env bash
git clone https://github.com/ThatOneCalculator/CalcFetch.git
cd CalcFetch/
sudo chmod +x calcfetch
echo /bin/ ~/.local/bin/ | xargs -n 1 sudo cp calcfetch
cd ..
sudo rm -r CalcFetch/
calcfetch
```

Features:
- Package manager and package count detection
- Support across all nerdfonts
- Uptime detection that is actually good
- Unlike neofetch, it uses almost no resources
- Portable
- POSIX compliant

Know issues:

- In [Cool-Retro-Term](https://github.com/Swordfish90/cool-retro-term), the coffee icon shows up as a Chinese character. To fix this, simply change the default font to a NerdFont you installed, or change the existing coffee icon to nf-fa-coffee from the [NerdFonts cheet sheet](https://www.nerdfonts.com/cheat-sheet).
- No support for BSD package managers/uptime calculations.
- When run with `/bin/sh` (POSIX) it works but the colors don't display properly on Linux sometimes
