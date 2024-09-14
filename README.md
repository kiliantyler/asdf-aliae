<div align="center">

# asdf-aliae [![Build](https://github.com/kiliantyler/asdf-aliae/actions/workflows/build.yml/badge.svg)](https://github.com/kiliantyler/asdf-aliae/actions/workflows/build.yml) [![Lint](https://github.com/kiliantyler/asdf-aliae/actions/workflows/lint.yml/badge.svg)](https://github.com/kiliantyler/asdf-aliae/actions/workflows/lint.yml)

[aliae](https://aliae.dev/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add aliae https://github.com/kiliantyler/asdf-aliae.git
```

aliae:

```shell
# Show all installable versions
asdf list-all aliae

# Install specific version
asdf install aliae latest

# Set a version globally (on your ~/.tool-versions file)
asdf global aliae latest

# Now aliae commands are available
aliae --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kiliantyler/asdf-aliae/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Kilian Tyler](https://github.com/kiliantyler/)
