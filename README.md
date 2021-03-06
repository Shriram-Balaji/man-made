<div align="center">
	<br>
	<br>
	<img width="360" src="media/logo.png" alt="Got">
	<br>
	<br>
	<br>
</div>


> Man Pages for Global Node Modules, right in the terminal.

[![Build Status](https://travis-ci.org/Shriram-Balaji/man-made.svg?branch=master)](https://travis-ci.org/Shriram-Balaji/man-made)

## Installation

```
npm install -g man-made
```

## How Does it Work?

This tools finds the list of global modules, and converts the package's readme into manual page documentations and stores them a directory called `.man-made` in the user's 🏡 HOME directory.

It also updates your shell configuration's MANPATH to use these newly added manual pages.

This works with most shells, including

- zsh
- bash
- fish
- csh
- ksh

## Usage

```
man package-name
```

### Note

Please make sure to spin up a new terminal session after installing to view the updated manual docs for the npm package, after installation.

## License

MIT
