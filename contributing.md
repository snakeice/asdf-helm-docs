# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test helm-docs https://github.com/snakeice/asdf-helm-docs.git "helm-docs --help"
```

Tests are automatically run in GitHub Actions on push and PR.
