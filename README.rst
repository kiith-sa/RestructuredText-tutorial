============================
RestructuredText with Sphinx
============================

-----------------
Setting up Sphinx
-----------------

^^^^^^^^^^
Windows XP
^^^^^^^^^^

* Install `Python 2.7 <http://www.python.org/ftp/python/2.7/python-2.7.msi>`_
* Install `Python Setuptools <http://pypi.python.org/packages/2.7/s/setuptools/setuptools-0.6c11.win32-py2.7.exe#md5=57e1e64f6b7c7f1d2eddfc9746bbaf20>`_ (a package manager)
* Set PATH environment variable for Python scripts:
  * Right-click *My Computer *
  * Go to the *Advanced* tab
  * Click the *Environment Variables* button
  * From *System Variables*, select *Path*, and click *Edit*
  * Assuming you installed Python to ``C:\Python27`` (the default), add this to the end of *Variable value*::

       C:\Python27;C:\Python27\Scripts

* Launch the terminal: Click *Start*, then *Run*, write ``cmd``, press Enter.
* Install Sphinx by typing the following commands to the terminal::

     easy_install pip
     pip install sphinx

* **Congratulations !** You succeeded in installing Sphinx!
* Now, still in the terminal, create a directory for your documentation and move there::

     md mydoc
     cd mydoc

* And finally generate a basic documentation template::

     sphinx-quickstart

* Quickstart will ask you some questions.
  The only questions that should interest you for now are:
   * *Project name:*
   * *Author name:*  
   * *Project version*
  Note thatt you can always change these later (you will be changing at least the version as your project develops).
  You can skip the others by pressing Enter.
  This will set up default settings.
  




 




TODO Win7, Ubuntu setup 

TODO use this file as example (link to source)

TODO source code highlighting

TODO more documentation links
  

