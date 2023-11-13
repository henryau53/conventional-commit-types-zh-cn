# conventional-commit-types

[![npm version](https://img.shields.io/npm/v/conventional-commit-types-zh-cn.svg?style=flat-square)](https://www.npmjs.org/package/conventional-commit-types-zh-cn)
[![npm downloads](https://img.shields.io/npm/dt/conventional-commit-types-zh-cn)](http://npm-stat.com/charts.html?package=conventional-commit-types-zh-cn&from=2023-11-01)

List of conventional commit types described in Simplified Chinese.

## Spec

Exports an object with a `types` key whose value is an object whose keys are type names and whose values are objects with key-value pairs such as `description` as string, optional `title` as string, etc. See [index.json](index.json). Any alternatives should follow the same spec.

## Etc.

Used by [commitizen/cz-conventional-changelog](https://github.com/commitizen/cz-conventional-changelog) for [commitizen/cz-cli](https://github.com/commitizen/cz-cli).

**(Archived)** Can be used with [kentcdodds/validate-commit-msg](https://github.com/kentcdodds/validate-commit-msg#types).

Commit types originally from:
* [Angular Git Commit Message Conventions](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#type)
* [commitizen/cz-conventional-changelog](https://github.com/commitizen/cz-conventional-changelog)

Created for [AndersDJohnson/conventional-commit-types-cli](https://github.com/AndersDJohnson/conventional-commit-types-cli).
