Variables
=========

Variables
---------

Variables in CCU are denoted using the ``/var <name>=<content>`` command. Variables in CCU are all of the ``string`` type in python. You can print variables using the ``/print``
function, then putting the variable name.


.. note:: CCU does not support the operation of variables more than 2 characters

**example**

/var x=i'm text

/print x

/end

**output**

i'm text

Lists
-----

Lists in CCU are similar to variables, but they carry a list value. To define a list, use the ``/list <name>`` command. Then you will be prompted to enter the number of
items. Enter them then enter the items. To print a list, do the same thing as a variable. You will be asked to enter the index "all" means the entire list.

**example**

``/list`` mylist

how many items> 2

0> a

1> b

``/print`` mylist

index> all

**outut**
a
