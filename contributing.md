# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test aliae https://github.com/kiliantyler/asdf-aliae.git "aliae --help"
```

Tests are automatically run in GitHub Actions on push and PR.
