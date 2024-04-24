# Neovim/Nvim plugin

[Neovim/Nvim](https://neovim.io) plugin for [Proto](https://moonrepo.dev/proto).

This plugin is called `nvim` because the executable is always named after the plugin name by proto (Neovims executable is `nvim`, confusing I know).

## Installation

This is a community plugin and is thus not built-in to Proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add nvim "source:https://raw.githubusercontent.com/z0rrn/proto-plugins/main/nvim/plugin.toml" --global
proto install nvim
```

### Per-project install

```shell
proto plugin add nvim "source:https://raw.githubusercontent.com/z0rrn/proto-plugins/main/nvim/plugin.toml"
proto pin nvim latest --resolve
```
