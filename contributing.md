# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test rye https://github.com/Azuki-bar/asdf-rye.git "rye --version"
```

Tests are automatically run in GitHub Actions on push and PR.
