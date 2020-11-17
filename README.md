<div align="center">

# asdf-topgrade ![Build](https://github.com/gorosz/asdf-topgrade/workflows/Build/badge.svg) ![Lint](https://github.com/gorosz/asdf-topgrade/workflows/Lint/badge.svg)

[topgrade](https://github.com/gorosz/topgrade) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add topgrade
# or
asdf plugin add https://github.com/gorosz/asdf-topgrade.git
```

topgrade:

```shell
# Show all installable versions
asdf list-all topgrade

# Install specific version
asdf install topgrade latest

# Set a version globally (on your ~/.tool-versions file)
asdf global topgrade latest

# Now topgrade commands are available
topgrade -h
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gorosz/asdf-topgrade/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Gergely orosz](https://github.com/gorosz/)
