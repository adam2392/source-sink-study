Source Sink Study Validation of Figures
---------------------------------------

To reproduce result figures generated in source-sink study.


System Requirements
===================
Generally to run the figure generation, one
simply needs a standard computer with enough RAM.
Minimally to generate the figures, probably a computer 
with 2GB RAM is sufficient.

We ran tests on computer with the following:

RAM: 16+ GB
CPU: 4+ cores, i7 or equivalent

Software: Mac OSX or Linux Ubuntu 18.04+. One should use Python3.6+.

Installation Guide
==================

Setup environment from pip if needed. If running this in Gigantum, then you can forego these instructions. 

.. code-block::

   # create and activate a virtual environment
   python -m venv .venv
   source .venv/bin/activate

   # install requirements file
   pip install -r requirements.txt

   # if dev versions are needed
   pip install https://api.github.com/repos/mne-tools/mne-bids/zipball/master
   pip install https://api.github.com/repos/mne-tools/mne-python/zipball/master


Instructions for Use
====================
Run the notebook from beginning to end to generate figures, 
by pointing the path to the `data/` folder here.