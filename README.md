# Ubuntu Bootstrap

This is a personal repository, nothing to see here.

## If you are me...

Run this on any new ubuntu machine to set it up just as you like it:

```bash
curl -Ls get.dannyb.co/bootstrap | bash
```

It is recommended to run this on a fully updated machine - update using:

```bash
apt update -y && apt upgrade -y && apt autoremove -y
reboot # if needed
```

## Additional information

This script:

- Installs the [rush](https://github.com/DannyBen/rush-cli) package manager.
- Connects rush to my [rush-repo](https://github.com/DannyBen/rush-repo).
- Runs the meta-package [my/bootstrap](https://github.com/DannyBen/rush-repo/blob/master/my/bootstrap/main) to install basic configuration packages.
