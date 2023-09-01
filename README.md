<div align="center">

# asdf-bfs [![Build](https://github.com/virtualroot/asdf-bfs/actions/workflows/build.yml/badge.svg)](https://github.com/virtualroot/asdf-bfs/actions/workflows/build.yml) [![Lint](https://github.com/virtualroot/asdf-bfs/actions/workflows/lint.yml/badge.svg)](https://github.com/virtualroot/asdf-bfs/actions/workflows/lint.yml)

[bfs](https://github.com/tavianator/bfs) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add bfs
# or
asdf plugin add bfs https://github.com/virtualroot/asdf-bfs.git
```

bfs:

```shell
# Show all installable versions
asdf list-all bfs

# Install specific version
asdf install bfs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bfs latest

# Now bfs commands are available
bfs --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/virtualroot/asdf-bfs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Alejandro Lazaro](https://github.com/virtualroot/)
