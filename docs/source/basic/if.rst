Conditionals
============

Conditionals
------------

In CCU, there are no elseif or else statements, only an if. An if statement is denoted using the ``/if <cond>`` command. Where cond is an operator (down).
To run other code if an if statement is true, use the ``execute <script>`` command. (Script is just a line of CCU code)

**example**

/if <cond>

execute /print cond fulflled

**output**

undefined

Operators
---------

In the previous example, cond is an operator. An operator is just ``<subOperator>=<check>``. Sub-operators include:

.. note:: operators only work for one characer

* ``+``: The mathematical plus operator
* ``-``: The mathematical minus operator
* ``*``: The mathematical times operator
* ``/``: The mathematical divide operator
* ``<var>``: a variable
* ``<list>{<index>}``: list[index]
