# Python 3.8 Virtual Environment

## Download Python 3.8.10

* <https://www.python.org/downloads/release/python-3810/>

   ![image](https://github.com/FlynntKnapp-python/python-38/assets/47562501/d32e4ba7-cd41-4aab-8700-8e2e08736fe6)

* Installation Options

   ![image](https://github.com/FlynntKnapp-python/python-38/assets/47562501/b257b0ac-e17c-4bf0-8415-d7fbc5a23117)

* Installation Location

   ![image](https://github.com/FlynntKnapp-python/python-38/assets/47562501/1bea47d4-fee0-433e-a8e2-990b4670fd2c)

## Reminders

* Don't add the new `python.exe` to the `PATH` variable. Only keep the primary Python installation in the `PATH` variable.

## Path to `python.exe`

* `C:\Users\FlynntKnapp\AppData\Local\Programs\Python\Python38\python.exe`

## Create Virtual Environment

* `pipenv --python C:\Users\FlynntKnapp\AppData\Local\Programs\Python\Python38\python.exe`
    * NOTE: Need to specify the path to the `python.exe` file in order for the virtual environment to be created with the correct version of Python. I think pipenv actually copies a version of the `python.exe` file into the virtual environment folder... Maybe?
