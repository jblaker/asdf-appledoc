<div align="center">

# asdf-appledoc [![Build](https://github.com/jblaker/asdf-appledoc/actions/workflows/build.yml/badge.svg)](https://github.com/jblaker/asdf-appledoc/actions/workflows/build.yml) [![Lint](https://github.com/jblaker/asdf-appledoc/actions/workflows/lint.yml/badge.svg)](https://github.com/jblaker/asdf-appledoc/actions/workflows/lint.yml)

[appledoc](https://github.com/tomaz/appledoc) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add appledoc https://github.com/jblaker/asdf-appledoc.git
```

appledoc:

```shell
# Now appledoc commands are available
appledoc --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jblaker/asdf-appledoc/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [<YOUR NAME>](https://github.com/jblaker/)
