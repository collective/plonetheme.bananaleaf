Introduction
============

The ``plonetheme.bananaleaf`` package uses the *theming & packaging* features
available in `plone.app.theming`_ to make the theme `bananaleaf`_ easily
available in `Plone 4.1`_ or higher.

.. image:: https://raw.github.com/collective/plonetheme.bananaleaf/master/plonetheme/bananaleaf/static/preview.png

Installation
============

Buildout
--------

To install this with buildout:

* Add ``plonetheme.bananaleaf`` to your ``plone.recipe.zope2instance`` section's ``eggs`` parameter::

    [instance]
    recipe = plone.recipe.zope2instance
    ...
    eggs =
        ...
        plonetheme.bananaleaf

* Re-run buildout, e.g. with::

    $ ./bin/buildout

.. _`bananaleaf`: http://www.freecsstemplates.org/preview/bananaleaf/
.. _`plone.app.theming`: http://pypi.python.org/pypi/plone.app.theming
.. _`Plone 4.1`: http://pypi.python.org/pypi/Plone/4.1rc2
