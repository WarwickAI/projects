<p align="center">
  <img alt="warwickai" src="https://raw.githubusercontent.com/warwickai/projects/main/projects/logo.svg" width=512/>
</p>

# Warwick AI Projects

This repository contains our projects resources (courses, tutorials) in the
form of a [Jupyter Book](https://jupyterbook.org/). A live version of this book
can be found at [https://projects.warwick.ai](https://projects.warwick.ai).

## Usage

### Building the book

If you'd like to develop and/or build the Warwick AI Projects book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a
   virtual environment)
3. (Optional) Edit the books source files located in the `projects/` directory
4. Run `jupyter-book clean projects/` to remove any existing builds
5. Run `jupyter-book build projects/`

A fully-rendered HTML version of the book will be built in `projects/_build/html/`.

## Contributors

We welcome and recognize all contributions. You can see a list of current
contributors in the [contributors
tab](https://github.com/warwickai/projects/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/)
and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
