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

## Environment & Version Managers

# Notebooks
* Jupyter Notebook
* Jupyter Lab
* Google Colab
* Azure Notebook

# IDEs & Editors
* Pycharm
* Visual Studio Code
* Spyder
* [repl.it (online)](https://repl.it/)


# Data Science
* Numpy
    ```python
    # generate random rgb color
    rgb = [k for k in (np.random.rand(3))]
    ```
* Pandas

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
* Tkintr
* Kivy

# Web Development
* Flask
* Django

# Executable Creation
## Windows
* PyInstaller
