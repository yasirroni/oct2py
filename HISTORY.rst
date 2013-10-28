.. :changelog:

Release History
---------------

1.0.1 (2013-10-27)
++++++++++++++++++

- Fixed bug preventing help(Oct2Py())


1.0.0 (2013-10-4)
+++++++++++++++++

- Support for Python 3.3
- Added logging to Oct2Py class with optional logger keyword.
- Added context manager
- Added support for unicode characters
- Improved support for cell array and sparse matrices
- Fixed: Changes to user .m files are now refreshed during a session
- Fixed: Remove popup console window on Windows


0.4.0 (2013-01-05)
++++++++++++++++++

- Singleton elements within a cell array treated as a singleton list
- Added testing on 64 bit architecture
- Fixed:  Incorrect Octave commands give a more sensible error message


0.3.6 (2012-10-08)
++++++++++++++++++
 
- Default Octave working directory set to same as OS working dir
- Fixed: Plot rending on older Octave versions


0.3.4 (2012-08-17)
++++++++++++++++++

- Improved speed for larger matrices, better handling of singleton dimensions


0.3.0 (2012-06-16)
++++++++++++++++++

- Added Python 3 support
- Added support for numpy object type


0.2.1 (2011-11-25)
++++++++++++++++++

- Added Sphinx documentation


0.1.4 (2011-11-15)
++++++++++++++++++

- Added support for pip


0.1.0 (2011-11-11)
++++++++++++++++++

- Initial Release