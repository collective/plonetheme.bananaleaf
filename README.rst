=====================
plonetheme.bananaleaf
=====================


Introduction
============

*plonetheme.bananaleaf* package uses the *theming & packaging* features
available in `plone.app.theming`_ to make the theme `bananaleaf`_ easily available in  Plone_.


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest version (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Screenshots
===========

Layout of the site when viewed in a computer resolution:

.. image:: https://raw.github.com/collective/plonetheme.bananaleaf/master/plonetheme/bananaleaf/static/preview.png


Features
========

- It's an installable Plone_ Theme package.
- After installation from Add-ons controlpanel, this theme is enabled automatically.
- Also it's a simple Diazo_ package (Zip file).
- It's have support for clean uninstallation.


Installation
============


Zipfile
-------

If you are an **end user**, you might enjoy installation via zip file import.

1. Download the `zip file <https://github.com/collective/plonetheme.bananaleaf/raw/master/bananaleaf.zip>`_.
2. Import the theme from the Diazo theme control panel.


Buildout
--------

If you are a **developer user**, you might enjoy installing it via buildout.

For install ``plonetheme.bananaleaf`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        plonetheme.bananaleaf


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'plonetheme.bananaleaf',
    ],


Enabling the theme
^^^^^^^^^^^^^^^^^^

Browse to ``http://yoursite/Plone/@@theming-controlpanel`` click on ``Enable`` on 
``Bananaleaf`` theme from the Diazo control panel. That's it!


Contribute
==========

- Issue Tracker: https://github.com/collective/plonetheme.bananaleaf/issues
- Source Code: https://github.com/collective/plonetheme.bananaleaf


License
=======

This package is licensed under the GPL Version 2.


Credits
-------

- Giacomo Spettoli (giacomo.spettoli at gmail dot com).
- Leonardo J. Caballero G. (leonardocaballero at gmail dot com).

.. _`Plone`: http://plone.org
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
.. _`bananaleaf`: http://www.freecsstemplates.org/preview/bananaleaf/
.. _`Diazo`: http://diazo.org
