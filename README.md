mcrio-wiki-mark
===============

[![Build Status](https://travis-ci.org/mcrio/wiki-mark.png)](https://travis-ci.org/mcrio/wiki-mark)

A minimal wiki markup language. Currently requires CoffeeScript.


Installation
------------

    npm install mcrio-wiki-mark


Usage
-----

    require('mcrio-wiki-mark')().compile('This could lead [[anywhere]]!')
    # => 'This could lead <a href="anywhere">anywhere</a>!'

The markup also supports backslash escaping and base path configuration.
For more examples, have a look at the test directory.


License
-------

The MIT License (MIT)

Copyright (c) 2013 Felix Rabe

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
