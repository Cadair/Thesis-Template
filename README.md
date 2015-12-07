PythonTeX Thesis Template
=========================


Information
-----------

This is based on the thesis template [here](https://github.com/kks32/phd-thesis-template).
To run this you need Python 2.7 with PythonTex, PDFLaTeX and BibTeX.
These dependancies are needed:

* [matplotlib](http://matplotlib.org/)
* [texfigure](https://github.com/Cadair/texfigure)

### Using conda

You can build the thesis from inside a conda environment as long as you have 
TexLive and pythontex installed in your system path. You can create a conda 
environment with the following command:

`conda create -n thesis python=2 matplotlib`

`pip install texfigure`

activate the new environment with:

`source activate thesis`

### Obtaining the data

Currently this is not accessible without my ssh key. This will be fixed as soon
as I can work out a techincal way of doing it, and I have had a break.


### Building the Thesis

Once the data has been obtained and the environment built, you can build the
pdf with the following command:

`python run.py thesis`

This will produce a file: `thesis/thesis.pdf`.


Copyright
---------

The LaTeX [here](https://github.com/kks32/phd-thesis-template) I used is 
copyright Krishna Kumar and licensed under the terms of the MIT licence. All
LaTeX code (not embedded Python) is licenced under the MIT license.
All Python code contained in this repository is copyright Stuart Mumford and 
is made availble under the MIT or 2-clause BSD license.

