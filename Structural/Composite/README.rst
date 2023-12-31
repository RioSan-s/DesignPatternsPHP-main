`Composite`__
=============

Purpose
-------

To treat a group of objects the same way as a single instance of the
object.

Examples
--------

-  a form class instance handles all its form elements like a single
   instance of the form, when ``render()`` is called, it subsequently
   runs through all its child elements and calls ``render()`` on them

UML Diagram
-----------

.. image:: uml/uml.png
   :alt: Alt Composite UML Diagram
   :align: center

Code
----

You can also find this code on `GitHub`_

Renderable.php

.. literalinclude:: Renderable.php
   :language: php
   :linenos:

Form.php

.. literalinclude:: Form.php
   :language: php
   :linenos:

InputElement.php

.. literalinclude:: InputElement.php
   :language: php
   :linenos:

TextElement.php

.. literalinclude:: TextElement.php
   :language: php
   :linenos:

Test
----

Tests/CompositeTest.php

.. literalinclude:: Tests/CompositeTest.php
   :language: php
   :linenos:

.. _`GitHub`: https://github.com/DesignPatternsPHP/DesignPatternsPHP/tree/main/Structural/Composite
.. __: http://en.wikipedia.org/wiki/Composite_pattern
