<div align="center">

# asdf-tre [![Build](https://github.com/MxNxPx/asdf-tre/actions/workflows/build.yml/badge.svg)](https://github.com/MxNxPx/asdf-tre/actions/workflows/build.yml) [![Lint](https://github.com/MxNxPx/asdf-tre/actions/workflows/lint.yml/badge.svg)](https://github.com/MxNxPx/asdf-tre/actions/workflows/lint.yml)


[tre](https://github.com/dduan/tre) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add tre
# or
asdf plugin add tre https://github.com/MxNxPx/asdf-tre.git
```

tre:

```shell
# Show all installable versions
asdf list-all tre

# Install specific version
asdf install tre latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tre latest

# Now tre commands are available
tre --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MxNxPx/asdf-tre/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [MxNxPx](https://github.com/MxNxPx/)
