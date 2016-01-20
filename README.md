orange3 conda recipes
---------------------

This repository contains [conda](http://conda.pydata.org/docs/index.html)
recipes for building Orange3

Run

    conda build pyqtgraph chardet bottlechest orange3

from within the source checkout to build the packages, and then

    conda install --use-local orange3

to install them into the current conda environment.

Prebuild packages (for win-64) for are also available at
[anaconda.org](https://conda.anaconda.org/ales-erjavec), use

    conda install -c https://conda.anaconda.org/ales-erjavec orange3
