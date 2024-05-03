# asdf-jetbrains-ideac [![Build](https://github.com/mbutov/asdf-jetbrains-ideac/actions/workflows/build.yml/badge.svg)](https://github.com/mbutov/asdf-jetbrains-ideac/actions/workflows/build.yml) [![Lint](https://github.com/mbutov/asdf-jetbrains-ideac/actions/workflows/lint.yml/badge.svg)](https://github.com/mbutov/asdf-jetbrains-ideac/actions/workflows/lint.yml)

[ideac](https://github.com/mbutov/asdf-jetbrains-ideac) plugin for the [asdf version manager](https://asdf-vm.com).

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `jq` - commandline JSON processor

# Install

Plugin:

```shell
asdf plugin add ideac
# or
asdf plugin add ideac https://github.com/mbutov/asdf-jetbrains-ideac.git
```

ideac:

```shell
# Show all installable versions
asdf list-all ideac

# Install specific version
asdf install ideac latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ideac latest

# Now ideac command is available
ideac --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mbutov/asdf-jetbrains-idea/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mbutov](https://github.com/mbutov/)
