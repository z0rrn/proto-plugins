# Minify CLI plugin

[Minify CLI](https://github.com/tdewolff/minify/tree/master/cmd/minify) plugin for [Proto](https://moonrepo.dev/proto).

## Installation

This is a community plugin and is thus not built-in to Proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add minify "source:https://raw.githubusercontent.com/z0rrn/proto-plugins/main/minify/plugin.toml" --global
proto install minify
```

### Per-project install

```shell
proto plugin add minify "source:https://raw.githubusercontent.com/z0rrn/proto-plugins/main/minify/plugin.toml"
proto pin minify latest --resolve
```
