# 2018 Spring astro hack
A repository for the 2018 Spring semester Society of Physics Students (SPS)
and Rutgers Astronomical Society (RAS) astro hack sessions.

## Getting started
Please download or clone the repository using:

    git clone https://github.com/rutgers-physics-ml/astro-hack-2018-spring


You will need Anaconda Python 3.6 or later, and we will supply all
necessary packages. Note that you will need an internet connection.
First add the `conda-forge` and `astropy` channels for access to some 
necessary Python packages:

    conda config --add channels conda-forge
    conda config --add channels astropy

Install the rest of the packages by running:

    conda env create -f environment.yml

These packages have now been installed on your system, to a virtual
environment in Anaconda Python named `astrohack`.

## Python virtual environments
You will need to *activate* the `astrohack` environment before executing any
code or serving any Jupyter notebooks. This can be accomplished by running:

    source activate astrohack

## Jupyter notebooks
You can view execute Jupyter notebooks (formerly IPython notebooks) by 
running the command:

    jupyter notebook

You can specify a browser type or port number by using the flags
    
    jupyter notebook --browser=firefox --port=8888

At this point, Jupyter will serve a notebook at `localhost:8888`. You can 
stop the notebook at any time by using the keyboard command `<Ctrl-c>`.

The Virtual Machine for the 29th March hack day can be found [here](https://drive.google.com/file/d/1ZWVIO1uXxbYZ5qhPhrNLQmMFAqh2XWCa/view).

