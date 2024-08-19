<div align="center">

# asdf-alejandra [![Build](https://github.com/jc00ke/asdf-alejandra/actions/workflows/build.yml/badge.svg)](https://github.com/jc00ke/asdf-alejandra/actions/workflows/build.yml) [![Lint](https://github.com/jc00ke/asdf-alejandra/actions/workflows/lint.yml/badge.svg)](https://github.com/jc00ke/asdf-alejandra/actions/workflows/lint.yml)

[alejandra](https://github.com/jc00ke/asdf-alejandra) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add alejandra
# or
asdf plugin add alejandra https://github.com/jc00ke/asdf-alejandra.git
```

alejandra:

```shell
# Show all installable versions
asdf list-all alejandra

# Install specific version
asdf install alejandra latest

# Set a version globally (on your ~/.tool-versions file)
asdf global alejandra latest

# Now alejandra commands are available
alejandra --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jc00ke/asdf-alejandra/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jesse Cooke](https://github.com/jc00ke/)
