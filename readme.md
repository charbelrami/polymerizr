# Polymerizr

## Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
  - [Build](#build)
  - [Run server](#run-server)
- [License](#license)

## Introduction

Polymer elements WYSIWYG editor

## Installation

```sh
$ npm i -g vulcanize polyserve
```

<!-- ```sh
$ npm i -g vulcanize crisper polyserve
``` -->

```sh
$ cd polymerizr && npm i && bower i
```

## Usage

```sh
$ cd polymerizr
```

### Build

```sh
$ vulcanize --inline-scripts --inline-css --strip-comments elements.html > build.html
```

<!-- ```sh
$ vulcanize --inline-scripts --inline-css --strip-comments elements.html | crisper --html build.html --js build.js
``` -->

### Run server

```sh
$ polyserve
```

## License

© 2015 Charbel Rami

[MIT](license)
