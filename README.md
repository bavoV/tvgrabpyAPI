# tvgrabpyAPI

###Summary

tv_grab_py_API is an API for creating xmltv compatible tv grabbers. It is the succesor of [tv_grab_nl_py version 2.2](https://github.com/tvgrabbers/tvgrabnlpy) making all of its functionallity available to the rest of the world.

###Requirements

 * Python 2.7.9 or higher
 * The [pytz module](http://pypi.python.org/pypi/pytz)
 * The [requests module](https://pypi.python.org/pypi/requests)
 * The [DataTreeGrab module](https://github.com/tvgrabbers/DataTree/)
 * Connection with the Internet

###Some features

 * No need for anybody who wants to create a grabber to know much about Python. You mainly must write one or more json data_defs defining one or more sources. These are [DataTreeGrab data_defs](https://github.com/tvgrabbers/DataTree/wiki/data_def_language) with some specific extensions.
 * All retrieved data is stored in an sqlite database which:
  * speeds up data retrieval
  * makes it possible to repeatetly access the data again while off-line  
 
 * Extensive list of user-settable options to give a user maximum oportunity to adapt the program to his or her need.
 * User setable genre translation tables with developer settable defaults.
 * Multiple language support (currently English and Dutch).
 * data_def updates are automatic.
 * theTVDB.com lookup.
