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

Oftentimes, we will use admonitions (e.g. note, warning, tip) in our curriculum. Create them via `RST directives <http://www.sphinx-doc.org/en/stable/usage/restructuredtext/basics.html#directives>`_.

.. attention::
   Now is not a time to `be distrated <https://giphy.com/gifs/afv-funny-fail-lol-3ornk9v2rS7mjf5qWA>`_!

.. caution::
   `Something bad <https://giphy.com/gifs/funny-crash-12MqSTw12YAnkI>`_ will happen if you ignore this!

.. danger::
   Be careful so you `don't get hurt <https://giphy.com/gifs/ice-everyone-dancer-9uyTvcNFUbpXa>`_!

.. error::
   Opps! Something `broke <https://giphy.com/gifs/car-chris-farley-tommy-boy-feO9ESQit0QM0>`_.

.. hint::
   If you want to know who ate the pizza, `this <https://giphy.com/gifs/hint-HvdQErvkFUsco>`_ might help.

.. important::
   Some information is `more important <https://giphy.com/gifs/sherlock-bbc-one-l0MYAY18Pxyxwu2xa>`_ than others.

.. note::
  Something like this might be helpful! If not, check `Google <https://google.com/>`_

.. tip::
   Sometimes a little help can `make things click <https://giphy.com/gifs/topher-grace-eric-foreman-Mjq9vmDuJlBKw>`_.

.. warning::
   Things could get bad if you don't `heed this <https://giphy.com/gifs/wes-anderson-moonrise-kingdom-warning-tyk39lYCnSMIo>`_!

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
