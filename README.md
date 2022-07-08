# Configurations

Configuration files for applications I currently use. For details of individual configs refer to the `README.md` file under the respective directories. 

## Using GNU stow

Stow is a useful application for managing dotfiles[^1], [^2].

To stow a config in the `app` directory,

``` sh
stow —target=~/ —ignore=“README.md” app
```

For example, to install the configuration for doom emacs in the `doom-emacs` directory,

``` sh
stow —target=~/ —ignore=“README.md” doom-emacs 
```

## Notes

Tested and verified to work on MacOS Monterey.

[^1]: https://venthur.de/2021-12-19-managing-dotfiles-with-stow.html
[^2]: https://alexpearce.me/2016/02/managing-dotfiles-with-stow/
