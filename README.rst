Get texts from Project Gutenberg, extract and format.

Code originally came from the `Open Shakespeare`_ project codebase
https://github.com/okfn/shakespeare.

.. _Open Shakespeare: http://openshakespeare.org/

Usage
*****

Download the gutenberg.py script (or clone the entire repo).

Use the script as follows::

    ./gutenberg.py {url-to-raw-gutenberg-text}

The cleaned version of the text will then be printed to standard out.

Tests
*****

Running the tests::

    nostests tests/test_gutenberg.py

Note that we have test data in ``tests/data``.

Copyright and License
*********************

Copyright 2005-2012 Open Knowledge Foundation. All material licensed under
the MIT license:

http://www.opensource.org/licenses/mit-license.php

