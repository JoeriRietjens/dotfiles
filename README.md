# dotfiles

These are my dotfiles. Take anything you want, but at your own risk.

## Installation

On a sparkling fresh installation of macOS:

```bash
sudo softwareupdate -i -a
xcode-select --install
```

The Xcode Command Line Tools includes `git` and `make` (not available on stock macOS). Now there are two options:

1. Install this repo with `curl` available:

```bash
bash -c "`curl -fsSL https://raw.githubusercontent.com/webpro/dotfiles/master/remote-install.sh`"
```

This will clone or download this repo to `~/.dotfiles` (depending on the availability of `git`, `curl` or `wget`).

1. Alternatively, clone manually into the desired location:

```bash
git clone https://github.com/webpro/dotfiles.git ~/.dotfiles
```
