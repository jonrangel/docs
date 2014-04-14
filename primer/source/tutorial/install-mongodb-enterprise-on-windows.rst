=====================================
Install MongoDB Enterprise on Windows
=====================================

.. default-domain:: mongodb

.. versionadded:: 2.5.3

Synopsis
--------

`MongoDB Enterprise <http://www.mongodb.com/products/mongodb-enterprise>`_
is available on select platforms, including Windows, and contains
support for several features related to security and monitoring. Use
this procedure to install and configure the MongoDB Enterprise on
Windows systems.

To install MongoDB Enterprise on other platforms, see
:doc:`/tutorial/install-mongodb-enterprise`.

Requirements
------------

MongoDB Enterprise Server for Windows requires Windows Server 2008
R2 or later. The MSI installer includes all other software dependencies.

Procedures
----------

.. the heading adornment in this section is unique to support
   different nesting orders in the include/source

Download MongoDB Enterprise for Windows
+++++++++++++++++++++++++++++++++++++++

Download the latest production release of `MongoDB Enterprise
<http://www.mongodb.com/products/mongodb-enterprise>`_

Install MongoDB Enterprise for Windows
++++++++++++++++++++++++++++++++++++++

Run the downloaded MSI installer. Make configuration choices as
prompted.

MongoDB is self-contained and does not have any other
system dependencies. You can install MongoDB into any folder
(e.g. ``D:\test\mongodb``) and run it from there. The installation
wizard includes an option to select an installation directory.

Run MongoDB Enterprise on Windows
+++++++++++++++++++++++++++++++++

.. include:: /tutorial/install-mongodb-on-windows.rst
   :start-after: start-windows-operate-database
   :end-before: end-windows-operate-database

Configure a Windows Service for MongoDB Enterprise
++++++++++++++++++++++++++++++++++++++++++++++++++

.. include:: /tutorial/install-mongodb-on-windows.rst
   :start-after: start-configure-windows-service
   :end-before: end-configure-windows-service
