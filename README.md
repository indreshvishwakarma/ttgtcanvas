ttgtcanvas
===============================

A Custom Jupyter Widget Library

Installation
------------

To install use pip:

    $ pip install ttgtcanvas

For a development installation (requires [Node.js](https://nodejs.org) and [Yarn version 1](https://classic.yarnpkg.com/)),

    $ git clone https://github.com/Totogoto/ttgtcanvas.git
    $ cd ttgtcanvas
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --overwrite --sys-prefix ttgtcanvas
    $ jupyter nbextension enable --py --sys-prefix ttgtcanvas

When actively developing your extension for JupyterLab, run the command:

    $ jupyter labextension develop --overwrite ttgtcanvas

Then you need to rebuild the JS when you make a code change:

    $ cd js
    $ yarn run build

You then need to refresh the JupyterLab page when your javascript changes.
