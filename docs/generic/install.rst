.. _install_page:

Installation Guide
==============================

BrainStat is available in Python and MATLAB.


Python installation
-------------------

BrainStat requires Python 3.7+. Assuming you have the correct version of Python
installed and aliased to `python`, you can install BrainStat by running the
following ::

    python -m pip install brainstat

Python Dependencies
+++++++++++++++++++++++

If you want to use the meta analysis module, you'll also have to download and install
the package pyembree. This package is only available through conda-forge: ::

    conda install -c conda-forge pyembree


MATLAB installation
-------------------

This toolbox is compatible with MATLAB versions R2019b and newer.

We recommend installing the toolbox through the Mathworks `FileExchange
<https://www.mathworks.com/matlabcentral/fileexchange/89827-brainstat>`_. Simply
download the file as a toolbox and open the .mltbx file in MATLAB.
Alternatively, you can install the same .mltbx file from our `GitHub Releases
<https://github.com/MICA-MNI/BrainStat/releases>`_.

If you don't want to install BrainStat as a MATLAB Toolbox, you can also simply
`download <https://github.com/MICA-MNI/BrainStat>`_ the repository and run
the following in MATLAB: ::

    addpath(genpath('/path/to/BrainStat/brainstat_matlab/'))

If you want to load BrainStat every time you start MATLAB, type ``edit
startup`` and append the above line to the end of this file. 
  
MATLAB Dependencies
+++++++++++++++++++++++

BrainStat relies on functionality included in the BrainSpace toolbox. Please see
the BrainSpace `installation guide <https://brainspace.readthedocs.io/en/latest/pages/install.html>`_ for 
installation instructions.

If you wish to open gifti files (required for data loader function) you will also need 
to install the `gifti library <https://www.artefact.tk/software/matlab/gifti/>`_.
