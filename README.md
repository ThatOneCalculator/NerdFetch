# NerdFetch
 A POSIX Linux/macOS fetch script using Nerdfonts

![Screenshot](https://i.imgur.com/6jfhfsv.png)

### Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- bc (optional, but most systems already have this)
- Pretty much any Linux distro/macOS

### To install and run:
### Arch based distros: (COULD BE USED TO UPDATE ON ARCH-BASED!)
```makepkg -si```
### Non-arch based distros:
Copy-paste this into your terminal:

```sh
# clone and go into repo
git clone https://github.com/Ohio2/NerdFetch.git
cd NerdFetch/
# install 
chmod +x nerdfetch
sudo scp nerdfetch /usr/local/bin/nerdfetch-ohio2
# go back and remove the download
cd ..
rm -rf NerdFetch/
# run
nerdfetch-ohio2
```
### Updating:
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
