<div align="center">

# asdf-ksops [![Build](https://github.com/janpieper/asdf-ksops/actions/workflows/build.yml/badge.svg)](https://github.com/janpieper/asdf-ksops/actions/workflows/build.yml) [![Lint](https://github.com/janpieper/asdf-ksops/actions/workflows/lint.yml/badge.svg)](https://github.com/janpieper/asdf-ksops/actions/workflows/lint.yml)

[ksops](https://github.com/janpieper/asdf-ksops) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add ksops
# or
asdf plugin add ksops https://github.com/janpieper/asdf-ksops.git
```

ksops:

```shell
# Show all installable versions
asdf list-all ksops

# Install specific version
asdf install ksops latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ksops latest

# Now ksops commands are available
ksops
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/janpieper/asdf-ksops/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jan Pieper](https://github.com/janpieper/)
