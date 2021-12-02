# monorepo-root

A seed nodejs project for a monorepo without packages.

This template includes github workflows definition. It assumes that npm is used to install packages / run commands. Supported commands: build, test, lint, semantic-release (all are optional).

Please setup scope in actions/setup-node@v2 of the publish step.

Also change details in LICENSE file.

Can be cloned with:
```
npx degit kshutkin/monorepo-root folder-name
```

Where folder-name should be replaced with desired folder name.

## Packages
