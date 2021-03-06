Research Project Template
=========================

|powered|   -   **cookiecutter branch:** |travis cookiecutter|

This is a project template built upon the package template provided by the Astropy project.

Using this project template, research projects can make use of the setup, installation, and documentation
infrastructure developed for the ``astropy`` core and affiliated packages.

For more information, see:

* The `documentation for this package template itself  <http://docs.astropy.org/projects/package-template/en/latest/>`_
* Astropy `documentation about this template <http://docs.astropy.org/en/latest/development/astropy-package-template.html>`_
* `The Affiliated Packages section of the Astropy web site <http://affiliated.astropy.org>`_
* `This template's Github code repository <https://github.com/astropy/package-template>`_


Using this project template
---------------------------

Using cookiecutter
^^^^^^^^^^^^^^^^^^

This package template makes use of the `cookiecutter
<https://cookiecutter.readthedocs.io/en/latest/index.html>`__ package to
make it easier to get started with the package template. You will need to
`install cookiecutter
<https://cookiecutter.readthedocs.io/en/latest/installation.html>`__ which
can be done easily using conda or pip::

  conda install -c conda-forge cookiecutter gitpython

  pip install cookiecutter gitpython


Once you have cookiecutter installed you can run::

  cookiecutter gh:nstarman/project_template

Which will ask you a series of questions to configure your project.


Improving the project template
------------------------------

If you want to modify this package template to add or fix things, the folder that
the user ends up with is ``{{ cookiecutter.package_name }}`` in this
repository. Everything in the repository that is not in this folder is not part
of the template that the user will have rendered.

For further information on writing templates for cookiecutter see `the cookiecutter docs <https://cookiecutter.readthedocs.io/en/latest/first_steps.html>`__.


.. |powered| image:: http://img.shields.io/badge/powered%20by-AstroPy-orange.svg?style=flat
    :target: http://www.astropy.org
    :alt: Powered by Astropy Badge

.. |travis cookiecutter| image:: https://travis-ci.com/nstarman/project_template.svg?branch=cookiecutter
    :target: https://travis-ci.com/nstarman/project_template
    :alt: Travis cookiecutter badge

