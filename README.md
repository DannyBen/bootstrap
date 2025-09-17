# Ubuntu / Arch Linux Bootstrap

This is a personal repository, nothing to see here.

## If you are me...

Run this on any new ubuntu or archlinux machine to set it up:

```bash
curl -Ls get.dannyb.co/bootstrap | bash
```

It is recommended to ensure the package manager database is up to date, 
and reboot if necessary.

```bash
# Ubuntu
sudo apt update -y && sudo apt upgrade -y && sudo apt autoremove -y

# Arch Linux
sudo pacman -Suy
```

## Additional information

This script:

- Installs the [rush](https://github.com/DannyBen/rush-cli) package manager.
- Connects rush to my [rush-repo](https://github.com/DannyBen/rush-repo).
- Runs the meta-package [my/bootstrap](https://github.com/DannyBen/rush-repo/blob/master/my/bootstrap/main) to install basic configuration packages.
