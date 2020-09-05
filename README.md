# CalcFetch
 A simple Linux fetch script using Nerdfonts

Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- Bash
- Pretty much any Linux distro

To install and run:

```sh
git clone https://github.com/thatonecalculator/calcfetch.git
cd calcfetch
sudo cp calcfetch ~/.local/bin/
sudo chmod +x ~/.local/bin/calcfetch 
cd ~
calcfetch
```

Know issue(s):

- In Cool-Retro-Term, the coffee icon shows up as a Chinese character. To fix this, replace the current coffee icon with `nf-fa-coffee` from [Nerdfont's Cheat Sheet](https://www.nerdfonts.com/cheat-sheet)