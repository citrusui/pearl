# Pearl

<img align="right" src="https://cloud.githubusercontent.com/assets/9056756/16823898/7802b488-4935-11e6-8249-e65b95610543.PNG"> My personal dotfiles for the [Pearl](https://github.com/pearl-core/pearl) package manager.

## Install

Make sure you already have Pearl [installed.](https://github.com/pearl-core/pearl#installation)

Add the following lines to `~/.config/pearl/pearl.conf`:

```
PEARL_PACKAGES["citrusui"]="https://github.com/citrusui/pearl"
PEARL_PACKAGES_DESCR["citrusui"]="Dotfiles adapted for use with Pearl."
```

Run the following command:

```sh
pearl install citrusui
```

Licensed under [MIT.](LICENSE.md)
