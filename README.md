# despiking
TroLUG Workshop: Despiking Data

## Install and run Jupyter notebook

Verify that Python 3 is available:
```
$ python --version
$ pip --version
```
Install `pipenv` (see [pipenv website](https://pipenv.pypa.io/en/latest/install/#installing-pipenv):
```
$ pip install --user pipenv
```
Clone this repository and change to directory:
```
git clone https://github.com/rzbrk/despiking.git
cd despiking
```
Install the Python environment from `Pipfile` using Python 3:
```
pipenv install --three
```
Run the Jupyter notebook:
```
pipenv run jupyter notebook despiking.ipynb
```
