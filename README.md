<div align="center">

# asdf-terraformer [![Build](https://github.com/jmcvetta/asdf-terraformer/actions/workflows/build.yml/badge.svg)](https://github.com/jmcvetta/asdf-terraformer/actions/workflows/build.yml) [![Lint](https://github.com/jmcvetta/asdf-terraformer/actions/workflows/lint.yml/badge.svg)](https://github.com/jmcvetta/asdf-terraformer/actions/workflows/lint.yml)

[Terraformer](https://github.com/GoogleCloudPlatform/terraformer) plugin for the [asdf version manager](https://asdf-vm.com).

Terraformer is a CLI tool to generate terraform files from existing infrastructure (reverse Terraform).

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
asdf plugin add terraformer https://github.com/jmcvetta/asdf-terraformer.git
```

terraformer:

```shell
# Show all installable versions
asdf list-all terraformer

# Install specific version
asdf install terraformer latest

# Set a version globally (on your ~/.tool-versions file)
asdf global terraformer latest

# Now terraformer commands are available
terraformer --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jmcvetta/asdf-terraformer/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jason McVetta](https://github.com/jmcvetta/)
