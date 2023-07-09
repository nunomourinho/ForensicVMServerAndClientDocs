=======
Typset
=======

Based on:
https://docutils.sourceforge.io/docs/ref/rst/directives.html#topic


.. DANGER::
   Beware killer rabbits!

.. CAUTION::
   Beware killer rabbits!

.. ERROR::
   Beware killer rabbits!

.. HINT::
   Beware killer rabbits!

.. IMPORTANT::
   Beware killer rabbits!

.. NOTE::
   Beware killer rabbits!

.. TIP::
   Beware killer rabbits!

.. WARNING::
   Beware killer rabbits!

.. admonition:: And, by the way...

   You can make up your own admonition too.

.. topic:: Topic Title

    Subsequent indented lines comprise
    the body of the topic, and are
    interpreted as body elements.

.. sidebar:: Optional Sidebar Title
   :subtitle: Optional Sidebar Subtitle

   Subsequent indented lines comprise
   the body of the sidebar, and are
   interpreted as body elements.

"To Ma Own Beloved Lassie: A Poem on her 17th Birthday", by
Ewan McTeagle (for Lassie O'Shea):

    .. line-block::

        Lend us a couple of bob till Thursday.
        I'm absolutely skint.
        But I'm expecting a postal order and I can pay you back
            as soon as it comes.
        Love, Ewan.

.. parsed-literal::

   ( (title_, subtitle_?)?,
     decoration_?,
     (docinfo_, transition_?)?,
     `%structure.model;`_ )


.. code:: python

  def my_function():
      "just a test"
      print 8/2

.. math::

  α_t(i) = P(O_1, O_2, … O_t, q_t = S_i λ)


.. epigraph::

   No matter where you go, there you are.

   -- Buckaroo Banzai

.. compound::

   The 'rm' command is very dangerous.  If you are logged
   in as root and enter ::

       cd /
       rm -rf *

   you will erase the entire contents of your file system.

   .. container:: custom

   This paragraph might be rendered in a custom way.

.. header:: This space for rent.


.. |reST| replace:: reStructuredText

Yes, |reST| is a long word, so I can't blame anyone for wanting to
abbreviate it.

I recommend you try |Python|_.

.. |Python| replace:: Python, *the* best language around
.. _Python: https://www.python.org/

Copyright |copy| 2023, |ForensicVM (c)| |---|
all rights reserved.

.. |copy| unicode:: 0xA9 .. copyright sign
.. |ForensicVM (c)| unicode:: ForensicVM U+2122
   .. with trademark sign
.. |---| unicode:: U+02014 .. em dash
   :trim:

.. |date| date::
.. |time| date:: %H:%M

Today's date is |date|.

This document was generated on |date| at |time|.

