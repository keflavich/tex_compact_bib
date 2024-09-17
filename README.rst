Making a REALLY compact bibliography
====================================

See `lmytime's branch <https://github.com/lmytime/tex_compact_bib>`__ for a more sophisticated version.

Tool for making an ApJ-style bibliography (e.g. using natbib so you can use \citep) in a really compact form, e.g.::

   Blah et al 2010 * Foo et al 1920 * Bar et al 1888

instead of::

   Blah et al 2010 
   Foo et al 1920 
   Bar et al 1888

.. image:: example.png

Instructions
------------

Include `bib_macros.tex`_ in your header, e.g.::

    \include{bib_macros}

or::

    \input{bib_macros}


REFERENCES
----------


 * https://tex.stackexchange.com/questions/5571/reduce-bibliography-to-one-line
 * http://www.ctex.org/documents/packages/table/paralist.pdf
 * https://tex.stackexchange.com/questions/11903/reduce-natbib-bibliography-to-one-line

And especially crucial for understanding the borderline-insane RPN choice in bst:

 * http://tug.ctan.org/info/bibtex/tamethebeast/ttb_en.pdf


.. _bib_macros.tex: bib_macros.tex


.. image:: https://d2weczhvl823v0.cloudfront.net/keflavich/tex_compact_bib/trend.png
   :alt: Bitdeli badge
   :target: https://bitdeli.com/free

