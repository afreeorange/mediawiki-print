Introduction
============

MediaWiki allows you to define the print stylesheet for your installation. Here's `a sample <http://en.wikipedia.org/w/index.php?title=Facebook&printable=yes>`_ of a printable page. Very 1995, eh? 

The goal is to provide a basic print stylesheet, with good layout and typographic sensibilities. I would like to add support for commonly used elements (like `the infobox <http://en.wikipedia.org/wiki/Template:Infobox>`_). I'll be happy when I can render most of `these pages <http://stats.grok.se/en/top>`_ satisfactorily. 

See the ``samples`` folder for progress. PDFs were generated on Firefox 17 with no header/footer information, and with background colors turned on.

Compatibility
=============

Developed/tested on a vanilla installation of **v1.20.2**. 

Installation
============

Replace the contents of ``MediaWiki:Print.css`` on your wiki with the ``mediawiki-print.css`` file.

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

MIT