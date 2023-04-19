<div align="center">

# asdf-pacaptr [![Build](https://github.com/splinter98/asdf-pacaptr/actions/workflows/build.yml/badge.svg)](https://github.com/splinter98/asdf-pacaptr/actions/workflows/build.yml) [![Lint](https://github.com/splinter98/asdf-pacaptr/actions/workflows/lint.yml/badge.svg)](https://github.com/splinter98/asdf-pacaptr/actions/workflows/lint.yml)


[pacaptr](https://github.com/rami3l/pacaptr) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `RTX_PACAPTR_VERSION=0.18.0`: set this environment variable in your shell config to load the correct version of tool 0.18.0.

# Install

Plugin:

```shell
asdf plugin add pacaptr
# or
asdf plugin add pacaptr https://github.com/splinter98/asdf-pacaptr.git
```

pacaptr:

```shell
# Show all installable versions
asdf list-all pacaptr

# Install specific version
asdf install pacaptr latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pacaptr latest

# Now pacaptr commands are available
pacaptr --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/splinter98/asdf-pacaptr/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Stephen Alderman](https://github.com/splinter98/)
