<div align="center">

# asdf-zarf [![Build](https://github.com/defenseunicorns/asdf-zarf/actions/workflows/build.yml/badge.svg)](https://github.com/defenseunicorns/asdf-zarf/actions/workflows/build.yml) [![Lint](https://github.com/defenseunicorns/asdf-zarf/actions/workflows/lint.yml/badge.svg)](https://github.com/defenseunicorns/asdf-zarf/actions/workflows/lint.yml)


[zarf](https://github.com/zarf-dev/zarf) plugin for the [asdf version manager](https://asdf-vm.com).

This ASDF plugin is not officially supported by the Zarf team. Use at your own risk. That being said, it has been in use in a variety of environments for several years now and is considered very stable.

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- *NIX system (tested on Linux and macOS)
- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add zarf https://github.com/defenseunicorns/asdf-zarf.git
```

zarf:

```shell
# Show all installable versions
asdf list-all zarf

# Install specific version
asdf install zarf X.Y.Z

# Set a version globally (on your ~/.tool-versions file)
asdf set -u zarf X.Y.Z

# Now zarf commands are available
zarf version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/defenseunicorns/asdf-zarf/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Defense Unicorns](https://github.com/defenseunicorns/)
