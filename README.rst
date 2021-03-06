.. image:: http://pybee.org/voc/static/images/voc-72.png
    :target: https://pybee.org/voc

VOC
===

.. image:: https://travis-ci.org/pybee/voc.svg?branch=master
    :target: https://travis-ci.org/pybee/voc

A transpiler that converts Python bytecode into Java bytecode.

This is experimental code. If it breaks, you get to keep all the shiny pieces.

What it does:

* Provides an API to let you programmatically create Java class files.

* Compiles Python 3.4 source files into Java class files, enabling you to run
  Python code on a JVM (including Android's VM).

It isn't a *completely* compliant Python 3.4 implementation - there are some
language features (like generators and context managers) that still need to be
implemented, and there is only a bare bones standard library implementation.
However, it is possible to convert simple Python programs, and even write
simple Android applications.

Tutorial
--------

To take VOC for a spin, run through the `Getting Started guide`_, then start
with `the first tutorial`_.

.. _Getting Started guide: http://voc.readthedocs.org/en/latest/intro/getting-started.html
.. _the first tutorial: http://voc.readthedocs.org/en/latest/tutorials/tutorial-0.html

Documentation
-------------

Documentation for VOC can be found on `Read The Docs`_.

Why "VOC"?
----------

The `Vereenigde Oostindische Compagnie (VOC)`_, or Dutch East India Company,
is often considered the be the world's first multinational corporation. It was
also the first company to issue shares, and facilitate the trading of those
shares. It was granted a 21 year monopoly to carry out trade activities in
Asia, primarily the Spice Islands - the Dutch East Indies. They established a
major trading port at Batavia - now Jakarta, on the island of Java (now part
of Indonesia). As a result of their monopoly, the VOC became an incredibly
valuable company, issuing an 18% annual dividend for almost 200 years.

VOC was... the world's first Enterprise using Java. (rimshot!)

VOC is also a backronym for "Vestigial Output Compiler". Or "Vexing Obtuse
Compiler". Or "Valuable Obscure Compiler". Or "Varigated Ocelot Calibrator".
It's your choice.

.. _Vereenigde Oostindische Compagnie (VOC): https://en.wikipedia.org/wiki/Dutch_East_India_Company

Community
---------

VOC is part of the `BeeWare suite`_. You can talk to the community through:

* `@pybeeware on Twitter`_

* The `BeeWare Users Mailing list`_, for questions about how to use the BeeWare suite.

* The `BeeWare Developers Mailing list`_, for discussing the development of new features in the BeeWare suite, and ideas for new tools for the suite.

Contributing
------------

To get started with contributing to VOC, head over to the `wiki`_.

If you experience problems with VOC, `log them on GitHub`_. If you
want to contribute code, please `fork the code`_ and `submit a pull request`_.

.. _BeeWare suite: http://pybee.org
.. _Read The Docs: http://voc.readthedocs.org
.. _@pybeeware on Twitter: https://twitter.com/pybeeware
.. _BeeWare Users Mailing list: https://groups.google.com/forum/#!forum/beeware-users
.. _wiki: https://github.com/pybee/voc/wiki/Your-first-VOC-contribution
.. _BeeWare Developers Mailing list: https://groups.google.com/forum/#!forum/beeware-developers
.. _log them on Github: https://github.com/pybee/voc/issues
.. _fork the code: https://github.com/pybee/voc
.. _submit a pull request: https://github.com/pybee/voc/pulls
