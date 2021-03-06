

.. include:: ../README.rst

Other Packages
--------------

A related promising package is `dimarray`_. It considers dimension names as a fundamental property of an array, and as such supports netCDF I/O format. It makes use of it in binary operations (broadcasting), transforms and indexing. 
It includes some of the nice features of pandas (e.g. axis alignment, optional
nan skipping) but extends them to N dimensions, with a behaviour closer 
to a numpy array. Some geo features are planned (weighted mean for latitude, 
indexing modulo 360 for longitude, basic regridding) but dimarray should remain broad in scope. Other packages are `larry`_ , `pandas`_ and `iris`_. 




.. _larry: http://berkeleyanalytics.com/la
.. _pandas: http://pandas.pydata.org 
.. _iris: http://scitools.org.uk/iris
.. _dimarray: dimarray.readthedocs.org
.. _spacegrids: https://github.com/willo12/spacegrids

