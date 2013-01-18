Introduction
============

MediaWiki allows you to define the print stylesheet for your installation. Here's `a sample <http://en.wikipedia.org/w/index.php?title=Facebook&printable=yes>`_ of a printable page. Very 1995, eh? 

The goal is to provide a basic print stylesheet, with good layout and typographic sensibilities. I would like to add support for commonly used elements/templates (like `the infobox <http://en.wikipedia.org/wiki/Template:Infobox>`_). I'll be happy when I can render most of `these pages <http://stats.grok.se/en/top>`_ satisfactorily. 

`Here's a sample <https://www.dropbox.com/s/euuiduca6ahery2/commit-05.pdf>`_.

Compatibility
=============

Developed/tested on a vanilla installation of MediaWiki **v1.20.2**. 

Installation
============

Replace the contents of ``MediaWiki:Print.css`` on your wiki with those of the ``mediawiki-print.css`` file.

Built Using
===========

* `Blueprint CSS <http://www.blueprintcss.org/>`_
* `Tim Murtaugh's HTML5 Reset <https://github.com/murtaugh/HTML5-Reset>`_
* `YUI Compressor <http://refresh-sf.com/yui/>`_
* `Jason Kottke's newsfeed <http://feeds.kottke.org/main>`_ for random URLs
* `Procssor <http://procssor.com/>`_
* `Malevole <http://www.malevole.com/mv/misc/text/>`_
* `Postmodernism Generator <http://www.elsewhere.org/pomo/>`_

License
=======

Copyright 2013 Nikhil Anand <nikhil@mantralay.org> 
http://mantralay.org

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.