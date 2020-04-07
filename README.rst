dff_calc
========

.. image:: https://img.shields.io/pypi/v/dff_calc.svg
    :target: https://pypi.python.org/pypi/dff_calc
    :alt: Latest PyPI version

.. image:: https://travis-ci.org.png
   :target: https://travis-ci.org
   :alt: Latest Travis CI build status

Simple dF/F calculation for neural calcium traces, based on https://www.nature.com/articles/nprot.2010.169

Usage
-----
1. ``from dff_calc import dff_calc``
2. Coerce your data to be in a (cell x time) 2D numpy array.
3. To calculate the dF/F, call ``dff = dff_calc(raw_data)``. Other parameters are listed in the docstring.

Installation
------------
``pip install dff-calc``

Requirements
------------
Python 3.6+, `numpy`, `pandas`, `scipy`

Licence
-------

Apache 2.0

Authors
-------

`dff_calc` was written by `Hagai Har-Gil <hagaihargil@protonmail.com>`_, graduate student in `Dr. Pablo Blinder's Lab. <pblab.tau.ac.il/en>`_
