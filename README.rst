==========================
ZenPacks.community.dummy
==========================


Description
===========
This ZenPack simply has the default files and directories after initial ZenPack creation.


Requirements & Dependencies
===========================

* Zenoss Versions Supported:  3.x, 4.x, 5.x
* External Dependencies: 
* Installation Notes: 

  - For Zenoss Core 3.x and 4.x, restart zenhub and zopectl
  - For Zenoss Service Dynamics, restart zenoss entirely after installation
  - For Zenoss 5, restart zenoss entirely after installation

Download
========
Download the appropriate package for your Zenoss version from the list
below.

* Zenoss 4.0+ `Latest Package for Python 2.7`_

ZenPack installation
======================

This ZenPack can be installed from the .egg file using either the GUI or the
zenpack command line. 

To install in development mode, find the repository on github and use the *Download ZIP* button
(right-hand margin) to download a tgz file and unpack it to a local directory, say,
/code/ZenPacks .  Install from /code/ZenPacks with::
  zenpack --link --install ZenPacks.community.dummy
  Restart zenoss after installation.

Device Support
==============

This ZenPack has been tested against:

* Zenoss 4.2.5 with ZUP 457
* Zenoss 5.0.7  


Change History
==============
* 1.0.0
   - Initial Release


.. External References Below. Nothing Below This Line Should Be Rendered

.. _Latest Package for Python 2.7: https://github.com/ZenossDevGuide/ZenPacks.community.dummy/blob/master/dist/ZenPacks.community.dummy-1.0.0-py2.7.egg?raw=true


