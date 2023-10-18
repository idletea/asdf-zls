<div align="center">

# asdf-zls [![Build](https://github.com/idletea/asdf-zls/actions/workflows/build.yml/badge.svg)](https://github.com/idletea/asdf-zls/actions/workflows/build.yml) [![Lint](https://github.com/idletea/asdf-zls/actions/workflows/lint.yml/badge.svg)](https://github.com/idletea/asdf-zls/actions/workflows/lint.yml)

[zls](https://github.com/idletea/asdf-zls) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add zls
# or
asdf plugin add zls https://github.com/idletea/asdf-zls.git
```

zls:

```shell
# Show all installable versions
asdf list-all zls

# Install specific version
asdf install zls latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zls latest

# Now zls commands are available
zls --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/idletea/asdf-zls/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Terry Kerr](https://github.com/idletea/)
