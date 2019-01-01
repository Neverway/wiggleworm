========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - tests
      - | |travis| |appveyor|
        | |codecov|
    * - package
      - | |commits-since|

.. |travis| image:: https://travis-ci.org/Neverway/wiggleworm.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/Neverway/wiggleworm

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/Neverway/wiggleworm?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/Neverway/wiggleworm

.. |codecov| image:: https://codecov.io/github/Neverway/wiggleworm/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/Neverway/wiggleworm

.. |commits-since| image:: https://img.shields.io/github/commits-since/Neverway/wiggleworm/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/Neverway/wiggleworm/compare/v0.0.0...master


.. end-badges

A python-based game engine

* Free software: BSD 2-Clause License

Installation
============

::

    git clone https://github.com/neverway/wiggleworm

Development
===========

To run the all tests run::

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
