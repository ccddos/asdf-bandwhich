<div align="center">

# asdf-bandwhich [![Build](https://github.com/ccddos/asdf-bandwhich/actions/workflows/build.yml/badge.svg)](https://github.com/ccddos/asdf-bandwhich/actions/workflows/build.yml) [![Lint](https://github.com/ccddos/asdf-bandwhich/actions/workflows/lint.yml/badge.svg)](https://github.com/ccddos/asdf-bandwhich/actions/workflows/lint.yml)

[bandwhich](https://github.com/imsnif/bandwhich) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add bandwhich
# or
asdf plugin add bandwhich https://github.com/ccddos/asdf-bandwhich.git
```

bandwhich:

```shell
# Show all installable versions
asdf list-all bandwhich

# Install specific version
asdf install bandwhich latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bandwhich latest

# Now bandwhich commands are available
bandwhich --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ccddos/asdf-bandwhich/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ning hao](https://github.com/ccddos/)
