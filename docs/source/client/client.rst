===========
User Guide
===========

There are client modules and tools for users to send commands to the PanDA server using standard HTTP methods.
The PanDA server, by default, listens on a port 25080 for plain HTTP and another port 25443 for HTTP over SSL.
Make sure that your local firewall doesn't block access to those ports.

The first part of this page is for end-users to use PanDA for their analysis,
while the second part is for developers and can be skipped unless you
intend to develop applications on top of Python API.

For end-users
==============

.. toctree::
   :maxdepth: 1

   panda-client
   monitoring
   prun
   phpo
   pbook
   notebooks/python.ipynb
   jupyter

For developers
==========================

.. toctree::
   :maxdepth: 1

   rest
   rest_idds
