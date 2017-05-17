# Pedro

[![NPM](https://img.shields.io/npm/v/pedro.svg)](https://www.npmjs.com/package/pedro)
[![Downloads](https://img.shields.io/npm/dm/pedro.svg)](http://npm-stat.com/charts.html?package=pedro)
[![pledge](https://bredele.github.io/contributing-guide/community-pledge.svg)](https://github.com/petrofeed/contribution/blob/master/community.md)

Pedro is a command line utility you can extend with plugins.
* **Built-in plugin manager**: Use the power of the npm ecosystem to search and install as many plugins as you want.
* **Aliases**: Pedro allows you to easily install and add any command line, even the one that haven't been created for Pedro.

## Usage

A plugin is a separate command line which name should start by `pedro-`. Here's an example how to install the [pedro-tether](https://github.com/PetroFeed/pedro-tether) plugin:

```shell
# install pedro-tether plugin
$ npm install pedro-tether -g

# use pedro-tether from pedro
$ pedro tether
```

## Installation

```shell
npm install pedro --save
```

[![NPM](https://nodei.co/npm/pedro.png)](https://nodei.co/npm/pedro/)


## Question

For support, bug reports and or feature requests please make sure to read our
<a href="https://github.com/petrofeed/contribution" target="_blank">community guideline</a> and use the issue list of this repo and make sure it's not present yet in our reporting checklist.

## Contribution

The open source community is very important to us. If you want to participate please make sure to read our <a href="https://github.com/petrofeed/contribution" target="_blank">guideline</a> before making a pull request. If you have any related project, adapter or other let everyone know in our wiki.

## License


The MIT License (MIT)

Copyright (c) 2017 Petrofeed Inc

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
