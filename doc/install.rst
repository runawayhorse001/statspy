.. _install:

==============
How to Install
==============

.. |rst| replace:: ``Results``:
..
	.. admonition:: Chinese proverb

	   If you only know yourself, but not your opponent, you may win or may lose.
	   If you know neither yourself nor your enemy, you will always endanger yourself. 
	   – idiom, from Sunzi’s Art of War

Clone the Repository
++++++++++++++++++++

.. code-block:: bash

	git clone git@github.com:runawayhorse001/statspy.git


Install
+++++++

.. code-block:: bash

	cd statspy
	pip install -r requirements.txt 
	python setup.py install

Uninstall
+++++++++

.. code-block:: bash

	pip uninstall statspy

Test
++++

.. code-block:: bash

	cd statspy/test
	python test1.py

|rst|	

.. code-block:: python


	[-0.7985165  -0.33687786  1.85808405 -1.05770596 -0.60614307  0.72978979
	  0.86686617  1.21733246 -1.15885016  0.90996324]

.. _Sphinx: http://www.sphinx-doc.org/en/master/
.. _reStructuredText: https://en.wikipedia.org/wiki/ReStructuredText
.. _LaTex: https://en.wikipedia.org/wiki/LaTeX