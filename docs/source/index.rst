Welcome to ForensicVM documentation!
===================================

**ForensicVM** is a project that allows forensic investigators to virtualize forensic images.

It is composed of an Autopsy plugin named ForensicVM client and a server named ForensicVM server.
The server was developed using Django and Python and should be installed on Debian 11. Debian 11 should be installed on a bare metal server.
It is not recommended to install it on a hypervisor because the ForensicVM server is the hypervisor. A nested setup is not recommended.

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
