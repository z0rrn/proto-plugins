# Hugo plugin

[Hugo](https://gohugo.io) plugin for [Proto](https://moonrepo.dev/proto).

This directory provides two files, one for the standard Hugo version and one for Hugo extended (with [limitations](#limitations-extended-version)).

## Installation

This is a community plugin and is thus not built-in to Proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install - standard version

```shell
proto plugin add hugo "source:https://raw.githubusercontent.com/z0rrn/proto-plugins/main/hugo/plugin-standard.toml" --global
proto install hugo
```

### Global install - extended version

```shell
proto plugin add hugo "source:https://raw.githubusercontent.com/z0rrn/proto-plugins/main/hugo/plugin-extended.toml" --global
proto install hugo
```

### Per-project install - standard version

```shell
proto plugin add hugo "source:https://raw.githubusercontent.com/z0rrn/proto-plugins/main/hugo/plugin-standard.toml"
proto pin hugo latest --resolve
```

### Per-project install - extended version

```shell
proto plugin add hugo "source:https://raw.githubusercontent.com/z0rrn/proto-plugins/main/hugo/plugin-extended.toml"
proto pin hugo latest --resolve
```

## Limitations extended version

The extended version is not available on all platforms:

Supported by the extended version:

- MacOS: everything
- Linux: only amd64 and arm64, not arm
- Windows: only amd64, not arm64

All other platforms are not supported! If you develop on a non-supported platform, please change the plugin URL to the standard version in your local `.prototools`.
