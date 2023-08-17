<div align="center">

# asdf-notation [![Build](https://github.com/bodgit/asdf-notation/actions/workflows/build.yml/badge.svg)](https://github.com/bodgit/asdf-notation/actions/workflows/build.yml) [![Lint](https://github.com/bodgit/asdf-notation/actions/workflows/lint.yml/badge.svg)](https://github.com/bodgit/asdf-notation/actions/workflows/lint.yml)

[notation](https://notaryproject.dev/docs/cli-reference/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add notation
# or
asdf plugin add notation https://github.com/bodgit/asdf-notation.git
```

notation:

```shell
# Show all installable versions
asdf list-all notation

# Install specific version
asdf install notation latest

# Set a version globally (on your ~/.tool-versions file)
asdf global notation latest

# Now notation commands are available
notation version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bodgit/asdf-notation/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Matt Dainty](https://github.com/bodgit/)
