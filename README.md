# codemods

This is a collection of codemods I have written to help me automate certain
tasks in the past.

Most use [ast-grep](https://github.com/ast-grep/ast-grep) but some may use
jscodeshift or other tools.

## Usage of ast-grep codemods

```sh
sg scan -r path-to-codemod.yml path-to-source-code
```

## List of codemods

| Name | Description |
| -- | -- |
| [chai-should-to-expect](./codemods/chai-should-to-expect.yml) | Convert `should` assertions to `expect` assertions |
