# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test topgrade https://github.com/gorosz/asdf-topgrade.git "topgrade -h"
```

Tests are automatically run in GitHub Actions on push and PR.
