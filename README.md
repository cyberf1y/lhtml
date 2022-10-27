#
lhtml

## Installation
```sh
git clone git@github.com:cyberf1y/lhtml.git
chmod +x lhtml/lhtml.py
ln -s "$PWD/lhtml/lhtml.py" ~/.local/bin/
```

## Name
*lhtml* - link HTML files

## Synopsis
```sh
lhtml.py [-h] [-o DIR] FILE [FILE ...]
```

## Description
*lhtml* is a tool for linking HTML files, allowing the reuse of HTML elements,
without relying on JavaScript.

### Imports
*lhtml* can reuse HTML elements with the attribute `import`.

### `import`
Setting the attribute `import=file.html` of an HTML element replaces it with the
HTML element in *file.html*.