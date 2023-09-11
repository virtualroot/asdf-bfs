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

- C compiler, GNU make, `bash`, `curl`, `tar`: generic POSIX utilities.
- `acl`, `attr`, `libcap`, `oniguruma` libs.

# Install

Dependencies:

To build bfs from source, you need to install some [dependencies](https://github.com/tavianator/bfs/blob/main/README.md#installation).

<pre>
<strong>Alpine Linux</strong>
# apk add acl{,-dev} attr{,-dev} libcap{,-dev} oniguruma-dev

<strong>Arch Linux</strong>
# pacman -S acl attr libcap oniguruma

<strong>Debian/Ubuntu</strong>
# apt install acl libacl1-dev attr libattr1-dev libcap2-bin libcap-dev libonig-dev

<strong>Fedora</strong>
# dnf install acl libacl-devel libattr-devel libcap-devel oniguruma-devel

<strong>NixOS</strong>
# nix-env -i acl attr libcap oniguruma

<strong>Void Linux</strong>
# xbps-install -S acl-{devel,progs} attr-{devel,progs} libcap-{devel,progs} oniguruma-devel

<strong>MacPorts</strong>
# port install oniguruma6

<strong>Homebrew</strong>
$ brew install oniguruma
</pre>

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
