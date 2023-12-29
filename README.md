# Yuck Syntax Highlighting for Micro Editor

This repository contains a syntax highlighting definition for `.yuck` files to be used with the [micro](https://micro-editor.github.io/) text editor.

## Installation

To install the syntax highlighting for `.yuck` files, follow these steps:

1. Clone this repository or download the `yuck.yaml` file directly.
2. Create a `syntax` directory in your micro configuration directory if it doesn't already exist. You can find your configuration directory by running `micro -version` and looking for the `CONFIG DIR` path.
3. Copy the `yuck.yaml` file into the `~/.config/micro/syntax` directory.
4. Restart micro or open a new instance of micro to begin using the syntax highlighting for `.yuck` files.

## Features

The `yuck.yaml` syntax file provides highlighting for:

- Comments
- Keywords (e.g., `defwidget`, `defwindow`, `defpoll`, etc.)
- Boolean literals (`true`, `false`)
- Numeric literals
- Variable names (colon-prefixed)
- String literals (with support for escape sequences)
- Brackets and braces for lists, arrays, or blocks
