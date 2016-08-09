++++
News
++++

.. contents:: Contents:
   :backlinks: none

.. _start:

SQLObject 3.1.0
===============

Released 31 Jun 2016.

Features
--------

* Add UuidCol.

* Add JsonbCol. Only for PostgreSQL.
  Requires psycopg2 >= 2.5.4 and PostgreSQL >= 9.2.

* Add JSONCol, a universal json column.

* For Python >= 3.4 minimal FormEncode version is now 1.3.1.

Documentation
-------------

* Developer's Guide extended to explain SQLObject architecture and how
  to create a new column type.

* Fix URLs that can be found; remove missing links.

* Rename reStructuredText file from \*.txt to \*.rst.

Source code
-----------

* Fix all `import *` using https://github.com/zestyping/star-destroyer.

Tests
-----

* Test are now run at Circle CI.

* Use pytest-cov for test coverage. Report test coverage
  via coveralls.io and codecov.io.

SQLObject 3.0.0
===============

Released 1 Jun 2016.

Features
--------

* Support for Python 2 and Python 3 with one codebase!
  (Python version >= 3.4 currently required.)

Minor features
--------------

* PyDispatcher (>=2.0.4) was made an external dependency.

Development
-----------

* Source code was made flake8-clean.

Documentation
-------------

* Documentation is published at http://sqlobject.readthedocs.org/ in
  Sphinx format.

`Older news`__

.. __: News5.html

.. image:: https://sourceforge.net/sflogo.php?group_id=74338&type=10
   :target: https://sourceforge.net/projects/sqlobject
   :class: noborder
   :align: center
   :height: 15
   :width: 80
   :alt: Get SQLObject at SourceForge.net. Fast, secure and Free Open Source software downloads