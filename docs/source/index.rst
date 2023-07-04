Welcome to ForensicVM documentation!
===================================

**ForensicVM** is a project that allows forensic investigators to virtualize forensic images.

It is composed by a Autopsy plugin, named ForensicVM client and a server, named ForensicVM server.
The server was developed using django, python and should be installed on debian 11. The debian 11 should be installed on a baremetal server.
It is not recomended to install on a hypervisor because the forensicVM server is the hypervisor. A nexted setup is not recomended.

The first step is to install the server. Head to :ref:`installation`

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
