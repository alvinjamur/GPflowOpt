------------
Introduction
------------

Install
--------
1. Install TensorFlow.
Please see instructions on the main TensorFlow `webpage <https://www.tensorflow.org/versions/r1.0/get_started/get_started>`_. You will need version 1.0. . We find that for many users pip installation is the fastest way to get going.

2. Install package
GPflowOpt is a pure python library for now, so you could just add it to your path (we use ``python setup.py develop``) or try an install ``python setup.py install`` (untested). You can run the tests with ``python setup.py test``. This approach however assumes
Another straightforward way to install GPflowOpt including all of its dependencies: ``pip install . --process-dependency-links``