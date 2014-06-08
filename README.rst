.. image:: https://badge.waffle.io/yarko/thinking.out.loud.png?label=ready&title=Ready 
 :target: https://waffle.io/yarko/thinking.out.loud
 :alt: 'Stories in Ready'
README
======

This is a sphinx-doc_ setup for github.io using ABlog_.

.. _sphinx-doc: http://sphinx-doc.org/

.. _ABlog: http://ablog.readthedocs.org/

The sources are in this repository and the build directory is pushed to 
``{yourname}.github.io`` repository.
If you want to start your own ``sphinx-blog``, clone this, and start
from the ``clean-blog`` branch (which is minimally setup).


Operation
---------

clone this repository, then either git-clone a parallel one, or create
a repository by its side or clone your ``{yourname}.github.io``.

From this, the sources::

  make html


When satisfied::

  make publish


