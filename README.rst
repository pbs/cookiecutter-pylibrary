======================
cookiecutter-pylibrary
======================

Cookiecutter_ template for a Python python library.

This template is inspired, but it's much simpler than the one of `ionelmc
<https://github.com/ionelmc/cookiecutter-pylibrary>`_ template.

Requirements
------------

Projects using this template have these minimal dependencies:

* Cookiecutter_ - just for creating the project
* Setuptools_ - for building the package, wheels etc. Now-days Setuptools is widely available, it shouldn't pose a
  problem :)

To get quickly started on a new system, just `install setuptools
<https://pypi.python.org/pypi/setuptools#installation-instructions>`_ and then `install pip
<https://pip.pypa.io/en/latest/installing.html>`_. That's the bare minimum required to install Cookiecutter_. To install
it, just run this in your shell or command prompt::

  pip install cookiecutter

Usage
-----

First generate your project::

  cookiecutter gh:pbs/cookiecutter-pylibrary

You will be asked for these fields:

.. list-table::
    :header-rows: 1

    * - Template variable
      - Default
      - Description
    * - ``project_name``
      - .. code:: python

            "Nameless"
      - Verbose project name, used in headings (docs, readme, etc).
    * - ``package_name``
      - .. code:: python

            "nameless"
      - Python package name (whatever you would import).
    * - ``project_url``
      - .. code:: python

            "http://github.com/pbs/python-nameless"
      - Repository URL where the source code is hosted
    * - ``docs_url``
      - .. code:: python

            "http://open.pbs.org"
      - The place where the documentation lives

.. _Tox: http://testrun.org/tox/
.. _Setuptools: https://pypi.python.org/pypi/setuptools
.. _Cookiecutter: https://github.com/audreyr/cookiecutter
