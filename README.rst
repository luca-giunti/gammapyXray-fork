Caveat: this is a work in progress. More details and examples will be added here

Folder name: TBD
=======

A Python tool for the analysis of Gamma-ray and X-ray data in a unified framework, using physically-motivated spectral models.

The scripts provided in this folder are built on Numpy, Scipy, Astropy, Gammapy, Naima and Sherpa. A software description is provided in the following publication: TBD

.. image:: http://img.shields.io/badge/powered%20by-AstroPy-orange.svg?style=flat
    :target: http://www.astropy.org/
.. image:: https://anaconda.org/conda-forge/gammapy/badges/installer/conda.svg

Installation and Set-up
+++++++++++++++++++++++++++++++++++++++++++++
These instructions assume that you have previously installed a version of `Anaconda <https://www.anaconda.com/products/distribution>`_ or `Miniconda <https://docs.conda.io/en/latest/miniconda.html>`_ on your machine.

Download the zip / clone the repo: TBD

To set-up the work environment with conda::

  conda create -n gammapyXray-0.1
  conda activate gammapyXray-0.1
  conda install -c https://cxc.cfa.harvard.edu/conda/ciao -c conda-forge ciao sherpa
  conda install -c conda-forge gammapy

Additionally, if you wish to combine the absorption models provided in Sherpa with the physical models provided by Naima, you have to `install Naima <https://naima.readthedocs.io/en/latest/installation.html>`_. TBD: show how this is done!

Optionally, to work in a `Jupyter Lab <https://jupyterlab.readthedocs.io/en/stable/>`_ notebook::
  
  conda install -c conda-forge jupyterlab


Acknowledging or Citing
+++++++++++++++++++++++++++++++++++++++++++++


If you use gammapyXray for work/research presented in a publication (whether directly, or as a dependency to another package), we ask that you please cite it using the following links

.. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.4701488.svg?style=flat
    :target: TBD
.. image:: https://archive.softwareheritage.org/badge/swh:1:dir:02e8a702ef6c9558a9f96d99bf6b9f41b5edcd34/
    :target: TBD

and also quote the related paper

Bibtex

If you have no specific place in your manuscript to cite the paper,

Contributing Code and Feedback
+++++++++++++++++++++++++++++++++++++++++++++
.. image:: https://img.shields.io/github/issues-pr/registerrier/gammapy-ogip-spectra
    :target: https://github.com/registerrier/gammapy-ogip-spectra/pulls
.. image:: https://img.shields.io/github/issues-pr-closed/registerrier/gammapy-ogip-spectra    
    :target: https://github.com/registerrier/gammapy-ogip-spectra/pulls


.. image:: https://img.shields.io/github/issues/registerrier/gammapy-ogip-spectra
    :target: https://github.com/registerrier/gammapy-ogip-spectra/issues
.. image:: https://img.shields.io/github/issues-closed/registerrier/gammapy-ogip-spectra?color=yellow    
    :target: https://github.com/registerrier/gammapy-ogip-spectra/issues

Licence
+++++++
This folder is licensed under a 3-clause BSD style license - see the
`LICENSE.rst <https://github.com/gammapy/gammapy/blob/master/LICENSE.rst>`_ file.

.. image:: https://anaconda.org/conda-forge/gammapy/badges/license.svg
    :target: TBD
    :alt: Licence