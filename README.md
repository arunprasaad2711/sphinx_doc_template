# A simple template for sphinx documentation

<!-- TOC -->

- [A simple template for sphinx documentation](#a-simple-template-for-sphinx-documentation)
  - [Need for this template](#need-for-this-template)
  - [So what is this?](#so-what-is-this)
  - [Dependencies](#dependencies)

<!-- /TOC -->

## Need for this template

Often, it became necessary for me to open a sphinx project with the exact same settings:

*   Include the python library ``recommonmark`` and enable markdown files. [Also, I prefer markdown personally]
*   Include ``sphinx_rtd_theme`` in the documentation.
*   Make a shell script to create a ``latex``, ``html``, and ``pdf`` version in one shot.

## So what is this?

This is a simple template for sphinx documentation that has incorporated the above three settings.

*   The ``conf.py`` file has 
    *   ``recommonmark`` and ``*.md`` extension enabled in it.
    *   the ``sphinx_rtd_theme`` has been included in it .
*   A ``bash`` script ``execute`` is present inside to enable ``latex``, ``html``, and ``pdf`` compilations.

The other configurations of the project are left as it is. Anyone using this template can go and tweak them in the configuration file.

## Dependencies

To use this template seamlessly, the following libraries are to be installed:

*   [recommonmark](https://recommonmark.readthedocs.io/en/latest/)
*   [sphinx-rtd-theme](https://sphinx-rtd-theme.readthedocs.io/en/stable/)
*   [sphinx](http://www.sphinx-doc.org/en/master/) version 2.00+
*   Bash and Make