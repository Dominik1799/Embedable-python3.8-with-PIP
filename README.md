# Embedable-python3.8-with-PIP
Embedable python 3.8 distribution with PIP prepared for use

Credit to: https://www.roytuts.com/installing-pip-with-embeddable-zip-python-in-windows/

This distribution can be used when packaging an app that relies on python and you dont want to rely on destination machine having python and all the required packages installed. 

To run a python program, use _python.exe_ in the root of the archive like so:

```
python.exe <python_file_name>
```

To install packages, use the same _python.exe_ like this:

```
python.exe -m pip install <package_name>
```
