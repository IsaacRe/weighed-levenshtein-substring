Weighted Levenshtein
--------------------

Codebase forked from https://github.com/infoscout/weighted-levenshtein

Install
~~~~~~~

.. code:: bash

   pip3 install weighted-levenshtein-substring

Usage
~~~~~

Use

.. code:: python

   from weighted_levenshtein import mod_lev

   distance: float = mod_lev(string, pattern)

To find the lowest edit distance between ``pattern`` and any substring
of ``string``.
