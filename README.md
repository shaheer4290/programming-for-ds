# Programming for Data Science

A practical Python workspace for learning programming fundamentals and applying them to data science.

## Overview

This repository contains lessons, notebooks, and examples covering:

- Python programming fundamentals
- Data manipulation with pandas
- Data visualization with Matplotlib and Seaborn
- Interactive development with Jupyter notebooks

## Requirements

- Python 3.14 or newer
- [uv](https://docs.astral.sh/uv/)

## Installation

Clone the repository and create the project environment:

```bash
git clone https://github.com/shaheer4290/programming-for-ds.git
cd programming-for-ds
uv sync
```

The project dependencies are declared in `pyproject.toml`. The `uv.lock` file records the resolved versions for reproducible installations.

## Installed Libraries

| Library | Purpose |
| --- | --- |
| Jupyter | Interactive notebooks and data science workflows |
| pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization built on Matplotlib |
| SciPy | Scientific computing and statistical analysis |
| SymPy | Symbolic mathematics and equation solving |

## Usage

Run the package command:

```bash
uv run programming-for-ds
```

Launch JupyterLab to work with the notebooks:

```bash
uv run jupyter lab
```

Lesson notebooks are stored in the `L1/` and `L2/` directories.

## Project Structure

```text
.
├── L1/                       # Lesson 1 notebooks
├── L2/                       # Lesson 2 notebooks
├── src/
│   └── programming_for_ds/   # Python package source
├── .gitignore
├── pyproject.toml            # Project metadata and dependencies
├── uv.lock                   # Locked dependency versions
└── README.md
```

## Development

Add a dependency with:

```bash
uv add package-name
```

Refresh the lockfile and synchronize the environment after dependency changes:

```bash
uv lock
uv sync
```

Run project commands through `uv run` so they use the managed environment.

## License

This project is intended for educational and learning purposes.
