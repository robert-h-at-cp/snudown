﻿SaidIt Snudown
=======

`Snudown` is a reddit-specific fork of the [Sundown](http://github.com/vmg/sundown)
Markdown parser used by GitHub, with Python integration added.

SaidIt changes:

* subreddits identified with 's' rather than 'r'

The SaidIt installer will install this snudown fork for you automatically.

Install
-----

    $ sudo apt-get install gperf
    $ cd ~/src
    $ git clone https://github.com/libertysoft3/snudown.git
    $ cd snudown
    $ git checkout v1.5.1
    $ sudo python setup.py install

Setup for development on Mac OS X
---------------------------------

For Mac OS X:
1. Install `afl-fuzz` via homebrew: `brew install afl-fuzz`
3. You can now install the module via `python setup.py install`
4. You may also compile snudown using the Makefile directly if you so wish


Thanks
------

Many thanks to @vmg for implementing the initial version of this fork!


License
-------

Permission to use, copy, modify, and distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
