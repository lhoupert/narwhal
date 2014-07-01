# Narwhal

[![Build Status](https://travis-ci.org/njwilson23/narwhal.svg?branch=master)](https://travis-ci.org/njwilson23/narwhal)

Narwhal is a Python library for manipulating and visualizing oceanographic
survey data.

![narwhal type hierarchy](https://rawgit.com/njwilson23/narwhal/master/classmap.svg)

The `Cast` and `CastCollection` types serialize themselves as zipped JSON
objects for data storage and sharing. WOCE CTD casts in NetCDF format can also
be read directly.

The `narwhal.plotting` submodule contains convenience methods for creating
attractive T-S diagrams, cast plots, and section plots.

![P17N T-S diagram](https://rawgit.com/njwilson23/narwhal/master/ts-demo.png)

Narwhal provides a wrapper for the
[Gibbs Seawater Toolbox](http://www.teos-10.org/pubs/gsw/html/gsw_contents.html)
in the `narwhal.gsw` submodule.

## Installation

    git clone https://github.com/njwilson23/narwhal.git
    pip install -r narwhal/requirements.txt
    pip install narwhal

## Dependencies
- Python 2.7+ or Python 3.2+
- numpy
- scipy
- requests
- dateutil
- six
- [karta](https://github.com/njwilson23/karta)
- matplotlib (optional; for plotting)
- C-compiler (optional; for GSW)

Narwhal is experimental. Also consider
[python-oceans](https://github.com/ocefpaf/python-oceans) and
[oce](https://github.com/dankelley/oce) (R).

