# NerdFetch
 A POSIX \*nix (Linux, macOS, Android, \*BSD, etc) fetch script using Nerdfonts

![Screenshot](https://bunnyt1c.s3.us-east-005.backblazeb2.com/calckeysoc/a987b0b2-9cf4-4147-ac01-1753afcd62a3.png)

### Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- Anything but Windows

### To install and run:

#### [Arch Linux](https://aur.archlinux.org/packages/nerdfetch/):

```sh
yay -S nerdfetch
nerdfetch
```

Make sure to replace `yay` with whatever AUR helper you use. 

#### [yiffOS](https://packages.yiffos.gay/nerdfetch):

```sh
bulge install nerdfetch
nerdfetch
```

#### Manually:

Copy-paste this into your terminal:

```sh
sudo curl -fsSL https://codeberg.org/thatonecalculator/NerdFetch/raw/branch/master/nerdfetch -o /usr/bin/nerdfetch
sudo chmod +x /usr/bin/nerdfetch
nerdfetch
```

#### Android with Termux:

Copy-paste this into Termux:

```sh
curl -fsSL https://codeberg.org/thatonecalculator/NerdFetch/raw/branch/master/nerdfetch -o /data/data/com.termux/files/usr/bin/nerdfetch
chmod a+x /data/data/com.termux/files/usr/bin/nerdfetch
nerdfetch
```

#### Run once:

Note that this will ***not*** install the program.
```sh
curl -fsSL https://codeberg.org/thatonecalculator/NerdFetch/raw/branch/master/nerdfetch | sh
```

### Features:
- Strong cross-OS compatability
- Not bloated
- Portable
- POSIX

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
- In FreeBSD, no hostname and no uptime
- In OpenBSD, no hostname and no uptime, and no package count
