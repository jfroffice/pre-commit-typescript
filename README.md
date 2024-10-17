# TypeScript mirror for pre-commit

Mirrors all* [TypeScript](https://www.typescriptlang.org/) releases for the [pre-commit](https://pre-commit.com/) hooks framework.

## Usage

Add the following to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/jfroffice/pre-commit-typescript
  rev: v5.6.2
  hooks:
    - id: typescript
```

Change [rev](https://pre-commit.com/#repos-rev) to the typescript version you want to use from the [available versions as tags](https://github.com/jfroffice/pre-commit-typescript/tags).
