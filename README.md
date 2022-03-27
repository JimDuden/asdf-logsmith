<div align="center">

# asdf-logsmith [![Build](https://github.com/JimDuden/asdf-logsmith/actions/workflows/build.yml/badge.svg)](https://github.com/JimDuden/asdf-logsmith/actions/workflows/build.yml) [![Lint](https://github.com/JimDuden/asdf-logsmith/actions/workflows/lint.yml/badge.svg)](https://github.com/JimDuden/asdf-logsmith/actions/workflows/lint.yml)


[logsmith](https://github.com/otto-de/logsmith) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `Python 3.8`
- `bash`, `curl`, `unzip`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add logsmith
# or
asdf plugin add logsmith https://github.com/JimDuden/asdf-logsmith.git
```

logsmith:

```shell
# Show all installable versions
asdf list-all logsmith

# Install specific version
asdf install logsmith latest

# Set a version globally (on your ~/.tool-versions file)
asdf global logsmith latest

# Now logsmith commands are available
logsmith --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/JimDuden/asdf-logsmith/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jim Duden](https://github.com/JimDuden/)
