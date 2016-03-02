# Jupyter Notebooks
:notebook: Jupyter notebooks code-along for CERN Study Group


# Setup :construction:
Python is a popular language for scientific computing, and great for general-purpose programming as well. Installing all of its scientific packages individually can be a bit difficult, so we recommend an all-in-one installer.

Regardless of how you choose to install it, please make sure you install Python version 3.x and not version 2.x.

I recommend you [download and install Anaconda 3](https://store.continuum.io/cshop/anaconda/) on your laptop.
This is an all-in-one installer, it is super easy to remove again.

## Windows
Download the default Python 3 installer. Use all of the defaults for installation except make sure to check **Make Anaconda the default Python**.

## Mac OS X
Download the default Python 3 installer. Use all of the defaults for installation.

## Linux
Download the default Python 3 installer. Use all of the defaults for installation.

## Python packages
We will need a few python packages:

* jupyter
* matplotlib
* numpy
* scipy
* ipythonblocks

Most of these are part of anaconda by
default. To install the others run the following commands in a new
terminal:
```bash
conda install scipy numpy matplotlib
pip install bash_kernel
python -m bash_kernel.install
pip install ipythonblocks
```

# Launching jupyter
You can launch `jupyter` by typing `jupyter notebook` into a terminal. This
should open a new browser window. If it does not have a look at your
terminal output. It should mention a URL at which you can reach the
notebook server. Most likely it will be http://localhost:8888.

(CERNiacs: use your laptop and not lxplus)
