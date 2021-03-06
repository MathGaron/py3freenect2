py3freenect2
===========

Python bindings for [libfreenect2](https://github.com/OpenKinect/libfreenect2).

This fork contains:
- Better handling of data (smart pointer instead of copy)
- Registration code
- Depth copied as float
- Output as BGRA, with no additional copy

Requirements
---------

- Python3 (python2 support : https://github.com/remexre/pyfreenect2; backwards compatibility to come)
- Numpy
- Scipy (as appropriated by python version) : 
- Python Imaging Library (used for scipy.misc.im* functions) : http://www.pythonware.com/products/pil/
- OpenCV

Installation
---------

To install, run `sudo python setup.py install`.

Usage
---------

For usage, see `test.py`.


TODO List
---------
 * Make the pipeline argument of Freenect2Device's constructor actually do something
 * Test everything

