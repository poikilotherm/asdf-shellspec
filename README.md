<div align="center">

# asdf-shellspec ![Build](https://github.com/poikilotherm/asdf-shellspec/workflows/Build/badge.svg) ![Lint](https://github.com/poikilotherm/asdf-shellspec/workflows/Lint/badge.svg)

[shellspec](https://github.com/shellspec/shellspec) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add shellspec
# or
asdf plugin add https://github.com/poikilotherm/asdf-shellspec.git
```

shellspec:

```shell
# Show all installable versions
asdf list-all shellspec

# Install specific version
asdf install shellspec latest

# Set a version globally (on your ~/.tool-versions file)
asdf global shellspec latest

# Now shellspec commands are available
shellspec --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/poikilotherm/asdf-shellspec/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Oliver Bertuch](https://github.com/poikilotherm/)
