# Transforming and Analyzing Data With DuckDB

## Companion material for the [O'Reilly live course](https://learning.oreilly.com/live-events/transforming-and-analyzing-data-with-duckdb/0642572418007/)

In this repository, you will find all live demos for the course.

Although `duckdb` can work independently of Python, this course
uses Jupyter notebooks. All statements (except for the paths
refering to the data) can also run in `duckdb-cli`.

The notebooks have a few advantages though:
* Displaying results as a `DataFrame´ is prettier.
* The notebooks work with a local installation (see `pyproject.toml`)
  and with Google Colab (no further installation necessary).
* Downloading the necessary data is included in the notebooks.
* For demonstrating the interoperability of Python and `duckdb`,
  notebooks would be necessary anyway.

## How can you work with the repository?

If you use a local installation, clone the repository,
install the necessary packages (`uv sync` if using `uv`,
otherwise create a `venv` and `pip install -r requirements.txt`).
Register the kernel with either `uv run python -m ipykernel install --user --name duckdb --display-name "duckdb"` or `python -m ipykernel install --user --name duckdb --display-name "duckdb"`.

If you want to work with Google Colab, you can directly open
the links to the notebooks below.

## Notebooks

* [01-Install_First_Query.ipynb](01-Install_First_Query.ipynb) [Colab](https://colab.research.google.com/github/datanizing/oreilly-duckdb/blob/main/01-Install_First_Query.ipynb)
* [02-Data_In_Out.ipynb](02-Data_In_Out.ipynb) [Colab](https://colab.research.google.com/github/datanizing/oreilly-duckdb/blob/main/02-Data_In_Out.ipynb)
* [03-SQL.ipynb](03-SQL.ipynb) [Colab](https://colab.research.google.com/github/datanizing/oreilly-duckdb/blob/main/03-SQL.ipynb)
* [04-Python_Integration.ipynb](04-Python_Integration.ipynb) [Colab](https://colab.research.google.com/github/datanizing/oreilly-duckdb/blob/main/04-Python_Integration.ipynb)
* [05-Performance.ipynb](05-Performance.ipynb) [Colab](https://colab.research.google.com/github/datanizing/oreilly-duckdb/blob/main/05-Performance.ipynb)
* [06-Data_Project.ipynb](06-Data_Project.ipynb) [Colab](https://colab.research.google.com/github/datanizing/oreilly-duckdb/blob/main/06-Data_Project.ipynb)
