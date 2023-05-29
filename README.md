<div align="center">

# asdf-rye [![Build](https://github.com/Azuki-bar/asdf-rye/actions/workflows/build.yml/badge.svg)](https://github.com/Azuki-bar/asdf-rye/actions/workflows/build.yml) [![Lint](https://github.com/Azuki-bar/asdf-rye/actions/workflows/lint.yml/badge.svg)](https://github.com/Azuki-bar/asdf-rye/actions/workflows/lint.yml)


[rye](https://rye-up.com/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `install`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add rye
# or
asdf plugin add rye https://github.com/Azuki-bar/asdf-rye.git
```

rye:

```shell
# Show all installable versions
asdf list-all rye

# Install specific version
asdf install rye latest

# Set a version globally (on your ~/.tool-versions file)
asdf global rye latest

# Now rye commands are available
rye --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Azuki-bar/asdf-rye/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Azuki-bar](https://github.com/Azuki-bar/)
