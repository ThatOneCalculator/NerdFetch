# NerdFetch
 A POSIX \*nix (Linux, macOS, \*BSD, etc) fetch script using Nerdfonts

<!-- ![Screenshot](https://i.imgur.com/and9kuQ.png) -->
![Screenshot](https://linus-sex.tips/YaceZlOLdx.png)

### Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- Linux/macOS/FreeBSD

### To install and run:

#### [Arch Linux](https://aur.archlinux.org/packages/nerdfetch/):

```sh
yay -S nerdfetch
nerdfetch
```

Make sure to replace `yay` with whatever AUR helper you use. 

#### [yiffOS](https://git.yiffos.gay/Packaging/packages/src/branch/main/nerdfetch):

```sh
bulge install nerdfetch
nerdfetch
```

#### Manually:

Copy-paste this into your terminal:

```sh
sudo curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/master/nerdfetch -o /usr/bin/nerdfetch
sudo chmod +x /usr/bin/nerdfetch
nerdfetch
```

#### Run once:

Note that this will ***not*** install the program.
```sh
curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/master/nerdfetch | sh
```

#### Android with Termux:

Copy-paste this into Termux:

```sh
curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/master/nerdfetch -o /data/data/com.termux/files/usr/bin/nerdfetch
chmod a+x /data/data/com.termux/files/usr/bin/nerdfetch
nerdfetch
```

### Features:
- Package manager and package count detection across many OSes
- Support across all nerdfonts
- Uptime detection that is actually good
- Unlike neofetch, it uses almost no resources and runs instantly
- Portable
- POSIX compliant

### OSes supported:
- Debian based Linux
- Ubuntu based Linux
- Arch based Linux
- RedHat based Linux
- SUSE based Linux
- Bedrock Linux
- Alpine Linux
- KISS Linux
- Void Linux
- Gentoo Linux
- Exherbo Linux
- NixOS Linux
- Solus Linux
- yiffOS Linux
- Slackware Linux\*
- macOS 10.x + 11.x
- Android

### Known issues:
- \*In Slackware Linux, make sure to have `/usr/sbin` in PATH
- In Android, no app count (instead counts `apt` if installed)
- In FreeBSD, no hostname and no uptime
- In OpenBSD, no hostname and no uptime, and no package count
