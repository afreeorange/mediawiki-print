MediaWiki allows you to define the print stylesheet for your installation. Here's [a sample](http://en.wikipedia.org/w/index.php?title=Facebook&printable=yes) of a printable page.

The goal is to provide a basic print stylesheet, with good layout and typographic sensibilities. I would like to add support for commonly used elements/templates (like [the infobox](http://en.wikipedia.org/wiki/Template:Infobox)). I'll be happy when I can render most of [these pages](http://stats.grok.se/en/top) satisfactorily. 

[Here's a sample](https://www.dropbox.com/s/euuiduca6ahery2/commit-05.pdf).

Compatibility
-------------

Developed/tested on a vanilla installation of MediaWiki **v1.20.2**. 

Installation
------------

Replace the contents of `MediaWiki:Print.css` on your wiki with those of the `mediawiki-print.css` file.

Built Using
-----------

* [Blueprint CSS](http://www.blueprintcss.org/>)
* [Tim Murtaugh's HTML5 Reset](https://github.com/murtaugh/HTML5-Reset>)
* [YUI Compressor](http://refresh-sf.com/yui/>)
* [Jason Kottke's newsfeed](http://feeds.kottke.org/main>) for random URLs
* [Procssor](http://procssor.com/>)
* [Malevole](http://www.malevole.com/mv/misc/text/>)
* [Postmodernism Generator](http://www.elsewhere.org/pomo/>)

License
-------

Copyright 2013 Nikhil Anand <mail@nikhil.io>

