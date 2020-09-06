# CalcFetch
 A simple Linux fetch script using Nerdfonts

![Screenshot](https://i.imgur.com/tlZt1X8.png)

Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- Bash
- Pretty much any Linux distro

To install and run:

```sh
git clone https://github.com/ThatOneCalculator/CalcFetch.git
cd CalcFetch/
sudo cp calcfetch ~/.local/bin/
sudo chmod +x ~/.local/bin/calcfetch 
cd ~
calcfetch
```

Features:
- Package manager and package count detection
- Support across all nerdfonts
- Uptime detection that is actually good
- Unlike neofetch, it uses almost no resources
- Portable
- Techically POSIX compliant

Know issue(s):

- In [Cool-Retro-Term](https://github.com/Swordfish90/cool-retro-term), the coffee icon shows up as a Chinese character. To fix this, simply change the default font to a NerdFont you installed.
