[![npm (scoped)](https://img.shields.io/npm/v/xpack.svg)](https://www.npmjs.com/package/xpack) 
[![license](https://img.shields.io/github/license/xpack/xpack-js.svg)](https://github.com/xpack/xpack-js/blob/master/LICENSE)

## The xPack tools collection

A `npm` package with the xPack command line tools.

## xPacks overview

**xPacks** are general purpose software C/C++ packages, intended to enhance code sharing and reusing during the development of C/C++ libraries and applications, much the same as **npm modules** do so nicely in the JavaScript ecosystem.

## Purpose

This package does not provides any functionality in itself, it is mainly a convenient way to installs all tools in the xPack collection in a single command.

## Prerequisites

If this is your first encounter with `npm`, you need to install the [node.js](https://nodejs.org/) JavScript run-time. The process is straighforward and does not polute the system locations significantly; just pick the current version, download the package suitable for your platform and install it as usual. The result is a binary program called `node` that can be used to execute JavaScript code from the terminal, and a link called `npm`, pointing to the `npm-cli.js` script, which is part of the node module that implements the npm functionality. On Windows, it is recommended to first install the [Git for Windows](https://git-scm.com/download/win) package.

## Easy install

The module is available as [**xpack**](https://www.npmjs.com/package/xpack) from the public repository; with `npm` already available, installing `xpack` is quite easy:

```bash
$ sudo npm install xpack --global
```

On Windows, global packages are installed in the user home folder, and do not require `sudo`.

The module provides the xPack executables, which is the reason to install it globally.

The development repository is available from the GitHub [xpack/xpack-js](https://github.com/xpack/xpack-js) project.

To remove `xmake`, the command is similar:

```bash
$ sudo npm uninstall xmake --global
```

(On Windows `sudo` is not required`).

## License

The original content is released under the [MIT License](https://opensource.org/licenses/MIT), with all rights reserved to [Liviu Ionescu](https://github.com/ilg-ul).

## Note

The xPack tools are currently under development. Functional versions will be available soon.
