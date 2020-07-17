# python setup

Create a virtual environment in the working directory

```
python3 -m venv .venv
```

Activate and install software

```
source .venv/bin/activate
pip install jupytext --upgrade
pip install jupyter
```

# .ipynb from .Rmd

To create a python jupyter notebook from and Rmd file

```
source .venv/bin/activate
jupytext --to notebook <filename>.Rmd
```

# Running a notebook

```
jupyter notebook <filename>.ipynb
```
