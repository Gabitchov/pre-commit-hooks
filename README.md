# pre-commit hooks

## Description

> Several hooks to use with [pre-commit](http://www.pre-commit.com)

## Installation

In your repository pre-commit config file add:

```yaml
repos:

- repo: ...

- repo: https://github.com/Gabitchov/pre-commit-hooks.git
    rev: (SHA1|TAG)
    hooks:
      - id: editorconfig-checker
```

## Hooks

### editorconfig-checker

Integration of [editorconfig-checker](https://github.com/editorconfig-checker/editorconfig-checker)'s check command as hook.
