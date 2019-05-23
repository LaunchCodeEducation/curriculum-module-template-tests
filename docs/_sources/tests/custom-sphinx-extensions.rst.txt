Custom Sphinx Extensions
========================

ReplIt Code Blocks
------------------

The ``replit`` extension extends the ``sourcecode`` directive to allow auto insertion of an external link to a repl.it project. The project is identified using the ``:slug:`` option, along with the ``replit_user`` setting in ``conf.py``.

Here's an example of the source:

::

   .. replit:: js
      :slug: reverse-Function

      function reverse(str) {
         let lettersArray = str.split('');
         let reversedLettersArray = lettersArray.reverse();
         return reversedLettersArray.join('');
      }

And here's how it renders:

.. replit:: js
   :slug: reverse-Function

   function reverse(str) {
      let lettersArray = str.split('');
      let reversedLettersArray = lettersArray.reverse();
      return reversedLettersArray.join('');
   }

External Links
--------------

External links should have ``target=_blank``, along with a small indicator icon to the right of the link text.

`LaunchCode's home page <https://www.launchcode.org/>`_

Internal links should *not* have these features.

:ref:`table of contents <toc>`

Ordered toctree Lists
---------------------

The main :ref:`table of contents <toc>` should use ``<ol>`` elements.

Bulletted lists should still use default ``<ul>`` styles:

- Does this have a bullet or a number?
- Style rule changes should only apply to ordered lists.

#. Ordered lists not in a toctree should still have numbers.
#. Do they? 

Admonition Icons
----------------

Styles for :ref:`admonition-styles` should include indicator icons to the left of the title.
