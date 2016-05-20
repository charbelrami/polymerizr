# Polymerizr

## Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
  - [Build](#build)
  - [Run local server](#run-local-server)
  - [Bump version](#bump-version)
- [License](#license)

## Introduction

Polymer elements WYSIWYG editor

## Installation

- Clone the repository
- `cd` into directory and install local dependencies

```sh
$ cd polymerizr && npm i && bower i
```

## Usage

- `cd` into directory

```sh
$ cd polymerizr
```

### Build

```sh
$ npm run build
```

### Run local server

```sh
$ npm run serve
```

### Bump version

```sh
$ npm version [<newversion> | major | minor | patch | premajor | preminor | prepatch | prerelease | from-git]
```

- Ensures the working tree is clean
- Updates dependencies
- Uninstalls extraneous packages
- Reduces duplication in the dependency tree
- Vulcanizes elements
- Bumps the version in package.json
- Updates the git index to match the working tree
- Creates a git tag
- Pushes all the refs, including annotated tags
- Publishes the package to the npm registry

## License

[MIT](license)
