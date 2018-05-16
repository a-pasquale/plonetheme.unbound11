====================
plonetheme.unbound11
====================

`Unbound11 Theme`_, is an installable Diazo theme for Plone 4


Introduction
============

*Unbound11 Theme* is an installable Plone Theme developed by 
`Andrew Pasquale`_ using the **theming** and **packaging** 
features available in `plone.app.theming`_.


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest versión (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Screenshots
===========

Layout of the site when viewed in a computer resolution:

.. image:: https://github.com/a-pasquale/plonetheme.unbound11/raw/master/plonetheme/unbound11/static/preview.png


Features
========

- It's an installable Plone Theme package.
- After installation from Add-ons controlpanel, this theme is enabled automatically.
- It's have support for clean uninstallation.
- Also it's a simple Diazo package (Zip file).


Installation
============


Zip file
--------

If you are an end user, you might enjoy installation via zip file import.

1. Download a `zip file <https://github.com/a-pasquale/plonetheme.unbound11/raw/master/plonetheme.unbound11.zip>`_.
2. Import the theme from the Diazo theme control panel.

Enabling the theme
^^^^^^^^^^^^^^^^^^

Select and enable the theme from the Diazo control panel. That's it!


Buildout
--------

If you are a developer, you might enjoy installing it via buildout.

For install ``plonetheme.unbound11`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        plonetheme.unbound11


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'plonetheme.unbound11',
    ],


Contribute
==========

- Issue Tracker: https://github.com/a-pasquale/plonetheme.unbound11/issues
- Source Code: https://github.com/a-pasquale/plonetheme.unbound11


License
=======

The project is licensed under the GPLv2.

Credits
-------

- Andrew Pasquale (andrew at elytra dot net).
- Kyle Homstead (khomstead at gmail dot com).

Contributors
------------

- Leonardo J. Caballero G. (leonardocaballero at gmail dot com).


.. _`Unbound11 Theme`: https://www.styleshout.com/templates/preview/Unbound11/index.html
.. _`Andrew Pasquale`: https://twitter.com/apasquale
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
