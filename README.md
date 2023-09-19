# PyWidgets

This is a custom collection of `PySide6` widgets, which makes it convenient to manage and use as submodules during development.

### Usage

```
git submodule add
```

### Widgets

| Widget                                                           | Description |
| ---------------------------------------------------------------- | ----------- |
| [PyFigureCanvas](./widgets/py_figure_canvas/py_figure_canvas.py) | TBD         |
| [PyGraphicsView](./widgets/py_graphics_view/py_graphics_view.py) | TBD         |

### Development

Use [Poetry](https://python-poetry.org/) as the package management tool.

#### Setup

- Windows (Install `Poetry` using `PowerShell` & [Chocolatey](https://chocolatey.org/))

```bash
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python -
$Env:Path += ";$HOME\AppData\Roaming\Python\Scripts"; setx PATH "$Env:Path"
```

- MacOS (Install `Poetry` using [Homebrew](https://brew.sh/))

```bash
brew install poetry
```

#### Environment

```bash
poetry config virtualenvs.in-project true
```

#### Install

- Install dependencies

```bash
poetry install
```

- Install a package

```bash
poetry add <package>
```

- Install a package as a development dependency

```bash
poetry add <package> -G dev
```

- Remove a package

```bash
poetry remove <package>
```

### Testing

```bash

```

### Coding Style

```bash
poetry run black -l 100 .
```
