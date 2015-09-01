[Proviola](http://mws.cs.ru.nl/proviola/), a tool for proof reanimation.

Usage
=====

1.  Run `coqdoc` on your sources.
2.  Run the `camera/camera.py` script on the generated HTML file. Optionally provide
    an output file.
3.  On the generated XML file (with an `.flm` extension by default), run an XSLT
    processor such as `xsltproc` to get an HTML document. The default XSL template is
    `proviola/coq/proviola.xsl`, which includes the required JavaScript and CSS.

There is a known bug in processing 'plain' scripts, not preprocessed by `coqdoc`.

Dependencies
============

-   The [lxml library](http://lxml.de/).

