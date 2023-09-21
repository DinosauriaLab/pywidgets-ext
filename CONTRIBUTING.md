# Contributing to pywidgets-ext

Thank you for your interest in contributing to `pywidgets-ext`! Here’s how you can contribute to the project.

## Setup Your Development Environment

### 1. Clone the Repository

```bash
git clone https://github.com/leoli0605/pywidgets-ext.git
cd pywidgets-ext
```

### 2. Set Up Poetry

Use [Poetry](https://python-poetry.org/) as the package management tool. Follow the installation and setup guide as provided in the README.

#### Windows

```bash
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python -
$Env:Path += ";$HOME\AppData\Roaming\Python\Scripts"; setx PATH "$Env:Path"
```

#### MacOS

```bash
brew install poetry
```

### 3. Install Dependencies

```bash
poetry install
```

## Coding Style

Please follow the coding style used in the project.

```bash
poetry run black -l 100 .
```

## Submitting Changes

1. **Create a Branch:** Once your development environment is set up, create a new branch for your work.

```bash
git checkout -b <branch-name>
```

2. **Make Changes:** Make your changes and commit them with a descriptive message.

```bash
git commit -m "Description of changes made"
```

3. **Push Changes:** Push your changes to your fork.

```bash
git push origin <branch-name>
```

4. **Create a Pull Request:** Go to the original repository and create a pull request. Describe your changes in detail and how they enhance the project.

### Note: Please ensure that your code passes all the tests before submitting a pull request.

## Providing Examples

It's crucial to include example content (`if __name__ == "__main__":`) in each widget. This allows users to directly execute `python -m pywidgets_ext.<widget>` to understand the purpose of each widget and how to use it effectively. By providing clear and concise examples, you contribute to a smoother user experience and encourage the adoption of the widgets.

Thank you for enhancing `pywidgets-ext` with valuable examples!

## Reporting Bugs

If you find a bug, please open an issue in the GitHub repository describing the bug and where you found it.

- Please make sure to read our [Code of Conduct](CODE_OF_CONDUCT.md) and adhere to it in all interactions within the project.

Thank you for your contribution to pywidgets-ext!
