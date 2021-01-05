Forklift
========

.. image:: https://readthedocs.org/projects/forklift/badge/?version=latest
    :target: https://forklift.readthedocs.io/
    :alt: Latest Docs

.. image:: https://travis-ci.org/pypa/forklift.svg?branch=master
    :target: https://travis-ci.org/pypa/forklift

.. image:: http://codecov.io/github/pypa/forklift/coverage.svg?branch=master
    :target: http://codecov.io/github/pypa/forklift?branch=master

.. image:: https://requires.io/github/pypa/forklift/requirements.svg?branch=master
     :target: https://requires.io/github/pypa/forklift/requirements/?branch=master
     :alt: Requirements Status


Forklift is the upload side of Warehouse, designed to replace the legacy code
base that currently powers `PyPI <https://pypi.python.org/>`_.

You can find more information in the `documentation`_.


Getting Started
---------------

Running a copy of Forklift locally requires using ``docker`` and
``docker-compose``. Assuming you have those two items, here are a number of
commands you can use:

.. code-block:: console

    $ # Start up a local environment
    $ make serve
    $ # Start up a local environment in debug mode (pdb enabled)
    $ make debug
    $ # Initialize the database and fill it with test data
    $ make initdb
    $ # Run the tests
    $ make tests
    $ # Build the documentation
    $ make docs
    $ # Run the various linters
    $ make lint


Discussion
----------

If you run into bugs, you can file them in our `issue tracker`_.

You can also join ``#pypa`` or ``#pypa-dev`` on Freenode to ask questions or
get involved.


.. _`documentation`: https://forklift.readthedocs.io/
.. _`issue tracker`: https://github.com/pypa/warehouse/issues


Code of Conduct
---------------

Everyone interacting in the Forklift project's codebases, issue trackers, chat
rooms, and mailing lists is expected to follow the `PSF Code of Conduct`_.

.. PSF Code of Conduct: https://github.com/pypa/.github/blob/main/CODE_OF_CONDUCT.md
