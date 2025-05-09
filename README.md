<div align="center">

# asdf-eza ![Build](https://github.com/lwiechec/asdf-eza/workflows/Build/badge.svg) ![Lint](https://github.com/lwiechec/asdf-eza/workflows/Lint/badge.svg)

[eza](https://github.com/eza-community/eza) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`.

# Install

Plugin:

```shell
asdf plugin add eza https://github.com/lwiechec/asdf-eza.git
```

eza:

```shell
# Show all installable versions
asdf list all eza

# Install specific version
asdf install eza latest

# Set a version globally (on your ~/.tool-versions file)
asdf set -u eza latest

# Now eza commands are available
eza --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/lwiechec/asdf-eza/graphs/contributors)!

# License

`asdf-eza` is more almost direct copy of [asdf-zoxide](https://github.com/nyrst/asdf-zoxide) by [nyrst](https://github.com/nyrst); kudos!

See [LICENSE](LICENSE) © [Siegfried Ehret](https://github.com/SiegfriedEhret/)
