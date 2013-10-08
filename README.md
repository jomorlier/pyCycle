This plugin provides basic thermodynamic cycle modeling tools for OpenMDAO. It's main feature
is the inclusion of a FlowStation variable that provides access to isentropic flow relationships.

Pre-Reqs
======================

OpenMDAO 
-------------
This is an OpenMDAO plugin, so we assume you have already installed a version of OpenMDAO. 

On OS-X it is strongly suggested that you setup Python, and other OpenMDAO pre-reqs with 
homebrew. You can follow these [detailed instructions](http://www.lowindata.com/2013/installing-scientific-python-on-mac-os-x/)
but once you have homebrew installed and setup, here is the short version: 

```
brew install git
brew install python
brew install gfortran
pip install numpy
pip install scipy
brew install freetype
pip install matplotlib
```

Cantera
------------
In addition, this plugin requires the [Cantera](https://code.google.com/p/cantera/) package
and python wrapper for it. You can [compile cantera from scratch](http://cantera.github.io/docs/sphinx/html/compiling.html), 
or follow the instructions below for a bit easier route. 

Windows
------------
Cantera provides [pre-compiled](https://code.google.com/p/cantera/downloads/list) binaries 
that are by far the easiest choice for windows. You should follow their instructions 
for the best way to install it and make sure it works. 

https://code.google.com/p/cantera/wiki/WindowsInstallation

Mac OS X
------------
Assume you've used homebrew to get OpenMDAO setup, then just use it to install Cantera too! 

```
brew install cantera
```

Linux
------------
You're best bet is to follow the official instructions(http://cantera.github.io/docs/sphinx/html/compiling.html). 


Installation
============================================

To view the Sphinx documentation for this distribution, type:

plugin docs pycycle

