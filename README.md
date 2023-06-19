# Python 3.8 Virtual Environment

## Download Python 3.8.10

* <https://www.python.org/downloads/release/python-3810/>

## Reminders

* Don't add the new `python.exe` to the `PATH` variable. Only keep the primary Python installation in the `PATH` variable.

## Path to `python.exe`

* `C:\Users\FlynntKnapp\AppData\Local\Programs\Python\Python38\python.exe`

## Create Virtual Environment

* `pipenv --python C:\Users\FlynntKnapp\AppData\Local\Programs\Python\Python38\python.exe`
    * NOTE: Need to specify the path to the `python.exe` file in order for the virtual environment to be created with the correct version of Python. I think pipenv actually copies a version of the `python.exe` file into the virtual environment folder... Maybe?
