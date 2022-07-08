# Doom Emacs Configuration

Follow the steps below to install. The default path is assumed to be `~/.doom.d`.

- Install [Doom Emacs](https://github.com/doomemacs/doomemacs)
- Replace all files in `~/.doom.d` directory with those in this repository, or use GNU stow as below,

``` sh
stow --target-dir=/~ --ignore="README.org" doom-emacs
```
  
- Follow post-install instructions in [config.org](config.org).
- Add `~/.emacs.d/bin` to `$PATH`
- Run `doom sync -u` from terminal to update all packages

[config.org](config.org) is a literate file sourced by `init.el` that contains customizations for individual packages.

