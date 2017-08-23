# ember-import-blueprints

This addon is created to provide the latest set of blueprints for older versions of Ember CLI.

Currently `ember-import-blueprints` is helpful for using the new RFC 176 import syntax in applications using Ember CLI <2.16.
This can be used after running `ember-modules-codemod` to keep future development up to date with the new imports.

After Ember 2.16 this addon will be kept up to date with any upcoming blueprint changes that backwards compatible although there are no major blueprint changes planned after 2.16.

> **NOTE** because this addon overwrites all of the blueprints provided by `ember-source` be sure to either remove this addon or keep it up to date with your `ember-source` version.

## Installation

```bash
ember install ember-import-blueprints
```

## Running

Any generator provided by `ember-source` will match the blueprints on `master` as of the latest logged commit.

## Changelog

### V 1.0.0

* Import blueprints from commit [`f5a63208`](https://github.com/emberjs/ember.js/tree/f5a63208f8d998425e15c7af1167f6d8fdb16f1e/blueprints)
