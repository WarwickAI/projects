<p align="center">
  <img alt="warwickai" src="https://raw.githubusercontent.com/warwickai/education/main/education/logo.png" width=256 height=256/>
</p>

# Warwick AI Education

This repository contains our education resources (courses, tutorials) in the form of a [Jupyter Book](https://jupyterbook.org/).
A live version of this book can be found at [https://education.warwick.ai](https://education.warwick.ai).

## Usage

### Building the book

If you'd like to develop and/or build the Warwick AI Education book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `education/` directory
4. Run `jupyter-book clean education/` to remove any existing builds
5. Run `jupyter-book build education/`

A fully-rendered HTML version of the book will be built in `education/_build/html/`.

## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/warwickai/education/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
