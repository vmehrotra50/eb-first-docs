===================
(Brief) Style Guide
===================

This page contains everything you need to know about code styling so we can keep it standardized across our team.

Sample Class
============

Here is an example of what a class should look like. More detailed explanations

Variables
=========

Make sure to:

- Keep all variables in the same area of the file (at the beginning of the class)
- Naming: use camel case and ensure the name is descriptive, but short
- Use private modifiers for all instance/class-specific variables

.. code-block:: java

   private final int coolDescriptiveName = value;

Constants
=========

All constants should be capitalized and underscored. These should only be used in RobotMap and Constants (see `Code Structure <https://ebfi-docs.readthedocs.io/en/latest/docs/code/code_structure_guide.html>`_)

.. code-block:: java

   public static final int THIS_IS_A_CONSTANT = value;

Methods
=======

All methods should be camel case and the name of the method/parameters should follow `variable naming conventions <https://ebfi-docs.readthedocs.io/en/latest/docs/code/code_structure_styling.html#variables>`_ above. Make sure to add comments detailing what the method does if it isn't obvious (e.g. comment a complicated algorithm or purpose of a method but you don't have to explain why you're using a print statement)

.. code-block:: java
   
   // purpose of method (if not obvious)
   public void descriptiveMethodName(param1, param2) {
       // code...
   }
