Accessibility Tests
===================

Text Block
----------

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris et bibendum nibh. Duis et semper ante. Mauris pretium rutrum congue. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aenean maximus urna ut leo tempor, at faucibus felis fermentum. Proin quis nisl sit amet felis pretium posuere sit amet id justo. Nam condimentum auctor turpis, nec consequat lectus mattis et. Suspendisse ornare maximus lectus vitae molestie. Proin mauris est, imperdiet nec sagittis sed, tristique sed neque. Proin et mauris sollicitudin risus pulvinar rutrum ultricies et orci. In elementum dolor sed augue viverra facilisis.

Nulla scelerisque orci leo, semper tincidunt neque eleifend vel. Nullam accumsan sapien sit amet libero malesuada convallis. Aliquam erat volutpat. Nam sodales dignissim massa, at sodales massa. Curabitur lacus massa, condimentum id mattis eu, hendrerit nec est. Quisque pretium ante ligula, ut aliquam ipsum blandit sit amet. Nulla vehicula arcu ligula, ac varius dui dictum ac. Pellentesque dapibus, nulla et aliquet tincidunt, libero leo aliquet lacus, mattis fermentum odio eros in augue. Sed eget dui bibendum, pellentesque orci sit amet, tincidunt enim. Vestibulum eu fringilla nisi. Ut posuere lorem eget sodales vulputate. Morbi consequat mi turpis, quis gravida ligula interdum placerat. Etiam vitae purus semper, consequat magna eget, ultrices ex. Ut eu neque odio. Proin elementum lectus quis ex suscipit dapibus.

Hyperlinks should appear `as so <https://google.com/>`_.

Inline Text
-----------

- *italic* text
- **bold** text
- ``verbatim`` text
- :code:`inline code` text

When you don't want **all** your text to be in :code:`inline code style` you can use ``:code:`your code text here``` or ````your code text here````

Code Blocks
-----------

Code block with no syntax via highlighting::

    string HelloWorld;
    int numberoftimes = 17;

    console.log(numberoftimes * HelloWorld);

Code block with syntax highlighting:

.. code-block:: python

   def sayHello():
    print("Hello World!")

   sayHello()

Admonitions
-----------

Oftentimes, we will use admonitions (e.g. note, warning, tip) in our curriculum. Create them via `RST directives <http://www.sphinx-doc.org/en/stable/usage/restructuredtext/basics.html#directives>`_. For proper usage of admonitions, see the `curriculum docs <https://education.launchcode.org/curriculum-docs/guide/admonitions.html>`_.


.. note:: 

   The Note is probably the most widely used admonition. It should be used to call attention to a an important point. Often, Notes will also deviate from the main flow of discussion a bit. 

.. warning:: 

   Use a Warning to emphasize a subtle or surprising fact that could cause students trouble.

.. tip:: 

   Use a Tip to 

.. admonition:: Question

   Questions are most often used in "Check Your Understanding" sections, and block out a self-check question that the reader should consider.

.. admonition:: Example

   Examples provide concrete instances of the topic at hand.

.. admonition:: Examples

   Like an Example, but plural (duh).
   
.. admonition:: Try It!

   Try It! admonitions call the reader to learn by doing. Use Try It! with a prompt or program that the reader should engage with to better understand a concept.

   A common pattern is to follow a Try It! with a Question related to the prompt.

.. admonition:: Fun Fact

   An interesting, but supplemental, fact related to the current discussion. Fun Fact admonitions should communicate to the reader that the content is not part of the lesson's objectives, but is something that might be interesting or useful. 

.. admonition:: Generic

   Sometimes, you just need to `stand out <https://giphy.com/gifs/nhl-hockey-ice-xUPGcJU55vuGH8Hfeo>`_.


Lists
-----

- bullets only
- more bullets

- sub bullets

  - these are the sub
  - items, they are so sub

1. numbered items
2. numbered items with sub items

   1. make sure to line up the first subm with the first character of parent line
   2. more sub

3. non numbered sub items

   - a thing
   - another thing
