# SQL highlighting in yaml multiline strings for VS Code 

Adds syntax highlight support for yaml multiline SQL strings in VS Code.

## Installation

Install `yaml-string-sql` from extensions (`ctrl + shift + x` or `cmd + shift + x` on mac).
> Also available on [marketplace.visualstudio.com](https://marketplace.visualstudio.com/items?itemName=huisben.yaml-string-sql)

## Example

[![Example](docs/demo.png)](docs/demo.py)

## Usage

Insert `--sql`, `--beginsql`, or `--begin-sql` at the beginning of the part of the string you would like highlighted and a semicolon, `--endsql`, or `--end-sql` at the end of the highlighted section.

### Keybindings

cmd+s (or ctrl+s on mac) - Insert the following snippet:
```
"""
--sql
SELECT
;
"""
```

## Requirements

- Visual Studio Code v1.32.0 recommended
- Comments at beginning and end of highlighted section in the string (see Usage section).

## Community
- 2020-04-15 forked from [python-string-css](https://github.com/ptweir/python-string-sql)

## Release Notes

### [1.0.0] - 2020-04-15
- Forked from python-string-css

