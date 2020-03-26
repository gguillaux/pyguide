# pyguide
A compendium of tricks and tips learned over the years working with Python

# Installation
## Python
* [Python.org](https://www.python.org/)
* [Anaconda](https://www.anaconda.com/)

## Packages
```python
# install packages from pypi passing through a proxy
pip install pandas --index-url https://pypi.org/simple/ --proxy https://yourproxy.com:8080


# install packages from github repo
pip install git+git://github.com/lynzt/python_people_names.git
# or
pip install https://github.com/pyinstaller/pyinstaller/tarball/develop


# install package ignoring ssl error
pip install --trusted-host=pypi.org --trusted-host=files.pythonhosted.org jinja2
```

## Package Managers
* [Pip](https://pip.pypa.io/en/stable/)
* [Conda](https://docs.conda.io/en/latest/)
* [Poetry](https://python-poetry.org/)

## Environment & Version Managers
* [PyEnv](https://github.com/pyenv/pyenv)
* [Virtualenv](https://virtualenv.pypa.io/en/latest/)
* [PipEnv](https://github.com/pypa/pipenv)

# Notebooks
* [Jupyter Notebook](https://jupyter.org/install.html)
* [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/)
* [Google Colab (online)](https://colab.research.google.com/)
* [Azure Notebook (online)](https://notebooks.azure.com/)

# IDEs & Editors
* [Pycharm](https://www.jetbrains.com/pycharm/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Spyder](https://www.spyder-ide.org/)
* [RStudio](https://solutions.rstudio.com/python/overview/)
* [repl.it (online)](https://repl.it/)


# Data Science
* Numpy
    ```python
    # generate random rgb color
    rgb = [k for k in (np.random.rand(3))]
    ```
* Pandas
* Dask

# Data Visualization
* Matplotlib
* Seaborn
* Altair
* Plotly
* Pygal
* Bokeh

# Machine Learning
* Scikit Learn
* PyTorch
* TensorFlow

# Web Scrapping
* Requests
* BeautifulSoup
* Selenium

# Desktop  Development
* PyQt5
* Tkinter
* Kivy

# Web Development
* [Flask](https://palletsprojects.com/p/flask/)
* Django

# Executable Creation
## Windows
* [PyInstaller](https://pyinstaller.readthedocs.io/en/stable/installation.html)

# Python for Finance & Trading
* [QuantEcon](https://quantecon.org/)
* Quantopian
* [NumFocus](https://numfocus.org/)