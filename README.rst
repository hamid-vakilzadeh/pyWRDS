========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions|
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/pyWRDS/badge/?style=flat
    :target: https://pyWRDS.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/hamid-vakilzadeh/pyWRDS/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/hamid-vakilzadeh/pyWRDS/actions

.. |version| image:: https://img.shields.io/pypi/v/pywrds.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/pywrds

.. |wheel| image:: https://img.shields.io/pypi/wheel/pywrds.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/pywrds

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/pywrds.svg
    :alt: Supported versions
    :target: https://pypi.org/project/pywrds

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/pywrds.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/pywrds

.. |commits-since| image:: https://img.shields.io/github/commits-since/hamid-vakilzadeh/pyWRDS/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/hamid-vakilzadeh/pyWRDS/compare/v0.0.0...main



.. end-badges

A package to the rescue of the WRDS users.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install pywrds

You can also install the in-development version with::

    pip install https://github.com/hamid-vakilzadeh/pyWRDS/archive/main.zip


Documentation
=============


https://pyWRDS.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
