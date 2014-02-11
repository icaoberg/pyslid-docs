.. P(y)rotein Subcellular Location Image Database documentation master file, created by
   sphinx-quickstart on Mon Jul 22 18:00:02 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

P(y)rotein Subcellular Location Image Database
==============================================

Contents:


.. toctree::
   :maxdepth: 2

   pyslid
   history

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

License
-------
| Copyright (C) 2011-2014 Murphy Lab
| Ray and Stephanie Lane Center for Computational Biology
| School of Computer Science
| Carnegie Mellon University

You should have received a copy of the license along with this program. For additional information visit http://murphylab.web.cmu.edu/software.

About
=====
pyslid is one of the python packages that was developed for `OMERO.searcher <http://murphylab.web.cmu.edu/software/searcher/>`_, an open-source content-based image search tool for the cell and computational biology community as described in

* Baek Hwan Cho, Ivan Cao-Berg, Jennifer Ann Bakal and Robert F. Murphy. 2012. `OMERO.searcher: content-based image search for microscope images <http://www.nature.com/nmeth/journal/v9/n7/full/nmeth.2086.html>`_. Nature Methods 9, 633-634.

pyslid along with `ricerca <https://github.com/icaoberg/ricerca>`_ are python packages built for mimicking the behavior of `Protein Subcellular Location Image Database (PSLID) <http://pslid.org/start.html>`_ by using `The Open Microscopy Environment <http://www.openmicroscopy.org/site>`_ as the subcellular location image collection manager.

Authors
-------
| Ivan Cao-Berg, Jennifer Bakal, Baek Hwan Cho and Robert F. Murphy
| `Ray and Stephanie Lane Center for Computational Biology <http://lane.compbio.cmu.edu/>`_
| `School of Computer Science <http://www.cs.cmu.edu/>`_
| `Carnegie Mellon University <http://www.cmu.edu/>`_

Dependencies
============
ricerca uses the following python packages

- `numpy <http://www.numpy.org/>`_
- `scipy <http://www.scipy.org/>`_
- mahotas v0.94
- milk v0.4.3
- pymorph v0.96
- pyslic v0.6.1

To install this prerequisites in Ubuntu 12.04, run in terminal::

	sudo apt-get install update
	sudo apt-get install python-numpy python-scipy python-setuptools
	sudo easy_install pip #run this command if you do not have pip
	sudo pip install mahotas==0.94
	sudo pip install pyslic==0.6.1

Installation
============
The source for ricerca can be found in 

- `github <https://github.com/icaoberg/pyslid>`_

For convenience, an alternative copy is also kept up to date

- `bitbucket <git@bitbucket.org:icaoberg/pyslid.git>`_

To install the latest version of pyslid from the repository, run::

	git clone git@github.com:icaoberg/pyslid.git
	cd pyslid
	sudo python setup.py install
	cd ..
