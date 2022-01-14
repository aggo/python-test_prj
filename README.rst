========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-test_prj/badge/?style=flat
    :target: https://python-test_prj.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/aggo/python-test_prj/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/aggo/python-test_prj/actions

.. |requires| image:: https://requires.io/github/aggo/python-test_prj/requirements.svg?branch=main
    :alt: Requirements Status
    :target: https://requires.io/github/aggo/python-test_prj/requirements/?branch=main

.. |codecov| image:: https://codecov.io/gh/aggo/python-test_prj/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://codecov.io/github/aggo/python-test_prj

.. |version| image:: https://img.shields.io/pypi/v/test-prj.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/test-prj

.. |wheel| image:: https://img.shields.io/pypi/wheel/test-prj.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/test-prj

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/test-prj.svg
    :alt: Supported versions
    :target: https://pypi.org/project/test-prj

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/test-prj.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/test-prj

.. |commits-since| image:: https://img.shields.io/github/commits-since/aggo/python-test_prj/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/aggo/python-test_prj/compare/v0.0.0...main



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install test-prj

You can also install the in-development version with::

    pip install https://github.com/aggo/python-test_prj/archive/main.zip


Documentation
=============


https://python-test_prj.readthedocs.io/


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
