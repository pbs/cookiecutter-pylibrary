======================
cookiecutter-pylibrary
======================

Cookiecutter_ template for a Python python library.

This template is much simpler than the one of `ionelmc
<https://github.com/ionelmc/cookiecutter-pylibrary>`_ template.

Requirements
------------

Projects using this template have these minimal dependencies:

* Cookiecutter_ - just for creating the project
* Tox_ - for running the tests
* Setuptools_ - for building the package, wheels etc. Now-days Setuptools is widely available, it shouldn't pose a
  problem :)

To get quickly started on a new system, just `install setuptools
<https://pypi.python.org/pypi/setuptools#installation-instructions>`_ and then `install pip
<https://pip.pypa.io/en/latest/installing.html>`_. That's the bare minimum to required install Tox_ and Cookiecutter_. To install
them, just run this in your shell or command prompt::

  pip install tox cookiecutter

Usage
-----

First generate your project::

  cookiecutter gh:mvmocanu/cookiecutter-pylibrary

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
    * - ``repo_name``
      - .. code:: python

            "python-nameless"
      - Repository name on github.
    * - ``package_name``
      - .. code:: python

            "nameless"
      - Python package name (whatever you would import).
    * - ``distribution_name``
      - .. code:: python

            "nameless"
      - PyPI distribution name (what you would ``pip install``).
    * - ``project_url``
      - .. code:: python

            "http://github.com/pbs/python-nameless"
      - Repository URL where the source code is hosted
