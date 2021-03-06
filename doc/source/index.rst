.. Workload Automation 2 documentation master file, created by
   sphinx-quickstart on Mon Jul 15 09:00:46 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Documentation for Workload Automation
================================================

Workload Automation (WA) is a framework for running workloads on real hardware devices. WA
supports a number of output formats as well as additional instrumentation (such as Streamline
traces). A number of workloads are included with the framework.


.. contents:: Contents


What's New
~~~~~~~~~~

.. toctree::
   :maxdepth: 1

   changes


Usage
~~~~~

This section lists general usage documentation. If you're new to WA2, it is 
recommended you start with the :doc:`quickstart` page. This section also contains
installation and configuration guides.


.. toctree::
   :maxdepth: 2

   quickstart
   installation
   device_setup
   invocation
   agenda
   configuration


Extensions
~~~~~~~~~~

This section lists extensions that currently come with WA2. Each package below
represents a particular type of extension (e.g. a workload); each sub-package of
that package is a particular instance of that extension (e.g. the Andebench
workload). Clicking on a link will show what the individual extension does, 
what configuration parameters it takes, etc.

For how to implement you own extensions, please refer to the guides in the 
:ref:`in-depth` section.

.. raw:: html

   <style>
   td {
      vertical-align: text-top;
   }
   </style>
   <table <tr><td>
  
.. toctree::
   :maxdepth: 2

   extensions/workloads

.. raw:: html

   </td><td>

.. toctree::
   :maxdepth: 2

   extensions/instruments


.. raw:: html

   </td><td>

.. toctree::
   :maxdepth: 2

   extensions/result_processors

.. raw:: html

   </td><td>

.. toctree::
   :maxdepth: 2

   extensions/devices

.. raw:: html

   </td></tr></table>

.. _in-depth:

In-depth
~~~~~~~~

This section contains more advanced topics, such how to write your own extensions
and detailed descriptions of how WA functions under the hood.

.. toctree::
   :maxdepth: 2

   conventions
   writing_extensions
   execution_model
   resources
   additional_topics
   daq_device_setup
   revent
   apk_workloads
   contributing

API Reference
~~~~~~~~~~~~~

.. toctree::
   :maxdepth: 5

   api/modules


Indices and tables
~~~~~~~~~~~~~~~~~~

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

