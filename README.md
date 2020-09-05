# CalcFetch
 A simple Linux fetch script using Nerdfonts

![Screenshot](https://i.imgur.com/VFuV7S5.png)

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

Know issue(s):

- In Cool-Retro-Term, the coffee icon shows up as a Chinese character. To fix this, replace the current coffee icon with `nf-fa-coffee` from [Nerdfont's Cheat Sheet](https://www.nerdfonts.com/cheat-sheet). This issue only seems to occur on Cool-Retro-Term, CalcFetch was tested in Gnome terminal, Deepin terminal, Kitty, and Alacritty and didn't have this problem. 
