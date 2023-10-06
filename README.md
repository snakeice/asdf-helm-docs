<div align="center">

# asdf-helm-docs [![Build](https://github.com/snakeice/asdf-helm-docs/actions/workflows/build.yml/badge.svg)](https://github.com/snakeice/asdf-helm-docs/actions/workflows/build.yml) [![Lint](https://github.com/snakeice/asdf-helm-docs/actions/workflows/lint.yml/badge.svg)](https://github.com/snakeice/asdf-helm-docs/actions/workflows/lint.yml)

[helm-docs](https://github.com/norwoodj/helm-docs) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add helm-docs
# or
asdf plugin add helm-docs https://github.com/snakeice/asdf-helm-docs.git
```

helm-docs:

```shell
# Show all installable versions
asdf list-all helm-docs

# Install specific version
asdf install helm-docs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global helm-docs latest

# Now helm-docs commands are available
helm-docs --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/snakeice/asdf-helm-docs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Rodrigo Bernardi](https://github.com/snakeice/)
