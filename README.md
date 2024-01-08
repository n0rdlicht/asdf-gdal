<div align="center">

# asdf-gdal [![Build](https://github.com/n0rdlicht/asdf-gdal/actions/workflows/build.yml/badge.svg)](https://github.com/n0rdlicht/asdf-gdal/actions/workflows/build.yml) [![Lint](https://github.com/n0rdlicht/asdf-gdal/actions/workflows/lint.yml/badge.svg)](https://github.com/n0rdlicht/asdf-gdal/actions/workflows/lint.yml)

[gdal](https://gdal.org) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gdal
# or
asdf plugin add gdal https://github.com/n0rdlicht/asdf-gdal.git
```

gdal:

```shell
# Show all installable versions
asdf list-all gdal

# Install specific version
asdf install gdal latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gdal latest

# Now gdal commands are available
ogrinfo --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/n0rdlicht/asdf-gdal/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Thorben Westerhuys](https://github.com/n0rdlicht/)
