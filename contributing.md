# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test pacaptr https://github.com/splinter98/asdf-pacaptr.git "pacaptr --version"
```

Tests are automatically run in GitHub Actions on push and PR.
