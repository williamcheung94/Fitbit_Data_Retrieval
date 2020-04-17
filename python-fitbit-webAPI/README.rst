python-fitbit-webAPI
=============
This is built off the work of the creators of the Fitbit Web API library linked here:
https://github.com/orcasgit/python-fitbit

The library has much more cabability then what is used for this project. We aim only to fetch the intra-day user data.
The script to run is getHealthData after the instalation of the Web API.

Installing and setting up the API can be seen in seteps 1 to 4 in this tutorial:
https://www.kdnuggets.com/2020/02/using-fitbit-web-api-python.html

The Fitbit website has discriptions of the data type can be found in the Fitbit site:https://dev.fitbit.com/build/reference/web-api/

! Notes from origional developers:
=============
Fitbit API Python Client Implementation

For documentation: `http://python-fitbit.readthedocs.org/ <http://python-fitbit.readthedocs.org/>`_

Requirements
============

* Python 2.7+
* `python-dateutil`_ (always)
* `requests-oauthlib`_ (always)
* `Sphinx`_ (to create the documention)
* `tox`_ (for running the tests)
* `coverage`_ (to create test coverage reports)

.. _python-dateutil: https://pypi.python.org/pypi/python-dateutil/2.4.0
.. _requests-oauthlib: https://pypi.python.org/pypi/requests-oauthlib
.. _Sphinx: https://pypi.python.org/pypi/Sphinx
.. _tox: https://pypi.python.org/pypi/tox
.. _coverage: https://pypi.python.org/pypi/coverage/

To use the library, you need to install the run time requirements:

   sudo pip install -r requirements/base.txt

To modify and test the library, you need to install the developer requirements:

   sudo pip install -r requirements/dev.txt

To run the library on a continuous integration server, you need to install the test requirements:

   sudo pip install -r requirements/test.txt
