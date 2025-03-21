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
| [add-extensions-to-imports](./codemods/add-extensions-to-imports.yml) | Add `.js` to extensionless imports |
| [chai-expect-to-node-assert](./codemods/chai-expect-to-node-assert.yml) | Convert chai `expect` assertions to `node:assert` assertions |
| [chai-should-to-expect](./codemods/chai-should-to-expect.yml) | Convert `should` assertions to `expect` assertions |
| [sinon-to-tinyspy](./codemods/sinon-to-tinyspy.yml) | Convert `sinon` spies to `tinyspy` spies |
