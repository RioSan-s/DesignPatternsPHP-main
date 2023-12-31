`Flyweight`__
=============

Purpose
-------

To minimise memory usage, a Flyweight shares as much as possible memory with similar objects. It
is needed when a large amount of objects is used that don't differ much in state. A common practice is
to hold state in external data structures and pass them to the flyweight object when needed.

UML Diagram
-----------

.. image:: uml/uml.png
   :alt: Alt Flyweight UML Diagram
   :align: center

Code
----

You can also find this code on `GitHub`_

Text.php

.. literalinclude:: Text.php
   :language: php
   :linenos:

Word.php

.. literalinclude:: Word.php
   :language: php
   :linenos:

Character.php

.. literalinclude:: Character.php
   :language: php
   :linenos:

TextFactory.php

.. literalinclude:: TextFactory.php
   :language: php
   :linenos:

Test
----

Tests/FlyweightTest.php

.. literalinclude:: Tests/FlyweightTest.php
   :language: php
   :linenos:

.. _`GitHub`: https://github.com/DesignPatternsPHP/DesignPatternsPHP/tree/main/Structural/Flyweight
.. __: https://en.wikipedia.org/wiki/Flyweight_pattern
