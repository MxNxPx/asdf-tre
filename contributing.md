# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test tre https://github.com/MxNxPx/asdf-tre.git "tre --help"
```

Tests are automatically run in GitHub Actions on push and PR.
