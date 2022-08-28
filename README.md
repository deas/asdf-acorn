<div align="center">

# asdf-acorn [![Build](https://github.com/deas/asdf-acorn/actions/workflows/build.yml/badge.svg)](https://github.com/deas/asdf-acorn/actions/workflows/build.yml) [![Lint](https://github.com/deas/asdf-acorn/actions/workflows/lint.yml/badge.svg)](https://github.com/deas/asdf-acorn/actions/workflows/lint.yml)


[acorn](https://docs.acorn.io/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add acorn
# or
asdf plugin add acorn https://github.com/deas/asdf-acorn.git
```

acorn:

```shell
# Show all installable versions
asdf list-all acorn

# Install specific version
asdf install acorn latest

# Set a version globally (on your ~/.tool-versions file)
asdf global acorn latest

# Now acorn commands are available
acorn --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/deas/asdf-acorn/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andreas Steffan](https://github.com/deas/)
