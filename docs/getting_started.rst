Getting Started
===============

This page details how to get started with molecool. 

Installation
------------

this is a code block::

    print('hello world')

Usage 
-----
Here is an example of using molecool

.. code-block:: python

    import molecool
    
    symbols, coordinates = molecool.open_pdb('water.pdb')

    print(symbols)
    print(coordinates)