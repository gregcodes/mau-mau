# Installation

## [Optional but recommended] Prepare a virtualenv

You need [Python3](https://www.python.org/downloads/) and you should really install this in a [virtualenv](https://docs.python.org/3/library/venv.html). This should work out of the box. If not, you might be on Linux and are bitten by [this](https://bugs.launchpad.net/ubuntu/+source/python3.4/+bug/1290847). `sudo apt-get install python3-pip` should solve the problem - otherwise have a look at the [pip documentation](https://pip.pypa.io/en/stable/installing/).

    $ python3 -m venv mau-mau-env
        
Activation of virtualenvs is sadly still one of the things that is not os independent, so you will hve to look [here](https://docs.python.org/3/library/venv.html#creating-virtual-environments) how to do that in your os. The most common cases are:

    $ source mau-mau-env/bin/activate  # most linux shells
    $ mau-mau-env\Scripts\activate.bat  # Windows cmd.exe

Deactivate with:

    $ deactivate

## Install from Github

Install the latest code directly from github:

    $ pip install https://github.com/obestwalter/mau-mau/zipball/master
    
To install a specific version just replace `master` with the version you want to install (e.g. `1.1.0`). The different versions can be seen in the [release section](https://github.com/obestwalter/mau-mau/releases) of a Github project.

## Install from a downloaded archive

On the [releases page](https://github.com/obestwalter/mau-mau/releases/) you can download zip archives and install them like:

    $ pip install </path/to/downloaded/zip/archive>

## [Not implemented] install directly from [PyPI](https://pypi.python.org/pypi)

This would mean uploading the package to the official Python Package Index (PyPI -- formerly known as the cheese shop -- documented [here](https://docs.python.org/3/distutils/packageindex.html)) ... it's not hard to do but not necessary for a learning tool like this, so I just mention it here, because that is the official way for "real" software. It then could be installed by simply typing:

    $ pip install mau-mau

