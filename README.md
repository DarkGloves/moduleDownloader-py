<h1 align=center> moduleDownloader-py </h1>
A module that downloads other modules from pypi in case they're not installed on your device.

## Installation
```sh
pip install pystyle
```
## Usage:
Its usage is very simple, you just have to follow this syntax:
```sh
from moduleDownloader impor getmodules
getmodules('colorama', 'termcolor', pipver=3)
import colorama
import termcolor
```
This program will check if the modules 'colorama' and 'termcolor' are avaiable.
<br>
You must change pipver=3 with the python version you are using (in my case python 3, so 3)
<br>
You can also add as many modules as you want.
<br>
Remember to import the modules after using getmodules() function.
