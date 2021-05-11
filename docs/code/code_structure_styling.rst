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

   private final type coolDescriptiveName = value;

Constants
=========

All constants should be capitalized and underscored. These should only be used in RobotMap and Constants (see `Code Structure <https://ebfi-docs.readthedocs.io/en/latest/docs/code/code_structure_guide.html>`_)

.. code-block:: java

   public static final type THIS_IS_A_CONSTANT = value;

Methods
=======

All methods should be camel case and parameters