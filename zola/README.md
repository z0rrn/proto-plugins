# Zola plugin

[Zola SSG](https://www.getzola.org) plugin for [Proto](https://moonrepo.dev/proto).

## Installation

This is a community plugin and is thus not built-in to Proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add zola "source:https://raw.githubusercontent.com/z0rrn/proto-plugins/main/zola/plugin.toml" --global
proto install zola
```

### Per-project install

```shell
proto plugin add zola "source:https://raw.githubusercontent.com/z0rrn/proto-plugins/main/zola/plugin.toml"
proto pin zola latest --resolve
```
