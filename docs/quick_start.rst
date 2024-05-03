Quick Start
===========

Installation
-----------------

.. _installation:

You can install statistic-tool from PyPI using the following command:

.. code-block:: python

   pip install statistic-tool

PyPI link: https://pypi.org/project/statistic-tool/


Quick Examples
-----------------

Sample:

.. code-block:: python

   from statistic-tool.sample import *

   get_sample_size(population_size = n, 
                population_deviation = std_dev, 
                margin_of_error = 0.01)
   