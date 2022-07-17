# Package `mybase-lucien`
This package is used for setting up base locales.
Pay attention, this package does not require the dependency of `selenium` while being installed by pip, but `selenium` is required to be installed if `myselenium` is imported.
To install:
```shell
pip install mybase-lucien
```
To import:
```python
import mybase_lucien
```

## Module `myip`
This deals the problems with ip adresses.
### Import
```python
from mybase_lucien import myip
```
### Function `get()`
It gets current outbound ip address.
- usage
```python
ip = myip.get()
```
- arguments

  There are no arguments.
- returned value
  
  A string value, which is the ip address. It would be empty if the program fails to fetch the ip address. 