Content Tests
=============

This set of tests is focused on a variety of content elements and directives that have special styling.

Table of Contents
-----------------

.. contents:: On this page

Text Block
----------

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris et bibendum nibh. Duis et semper ante. Mauris pretium rutrum congue. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aenean maximus urna ut leo tempor, at faucibus felis fermentum. Proin quis nisl sit amet felis pretium posuere sit amet id justo. Nam condimentum auctor turpis, nec consequat lectus mattis et. Suspendisse ornare maximus lectus vitae molestie. Proin mauris est, imperdiet nec sagittis sed, tristique sed neque. Proin et mauris sollicitudin risus pulvinar rutrum ultricies et orci. In elementum dolor sed augue viverra facilisis.

Nulla scelerisque orci leo, semper tincidunt neque eleifend vel. Nullam accumsan sapien sit amet libero malesuada convallis. Aliquam erat volutpat. Nam sodales dignissim massa, at sodales massa. Curabitur lacus massa, condimentum id mattis eu, hendrerit nec est. Quisque pretium ante ligula, ut aliquam ipsum blandit sit amet. Nulla vehicula arcu ligula, ac varius dui dictum ac. Pellentesque dapibus, nulla et aliquet tincidunt, libero leo aliquet lacus, mattis fermentum odio eros in augue. Sed eget dui bibendum, pellentesque orci sit amet, tincidunt enim. Vestibulum eu fringilla nisi. Ut posuere lorem eget sodales vulputate. Morbi consequat mi turpis, quis gravida ligula interdum placerat. Etiam vitae purus semper, consequat magna eget, ultrices ex. Ut eu neque odio. Proin elementum lectus quis ex suscipit dapibus. 

Images and Figures
------------------

Images and figures should be full-width unless the `:width:` or `:height:` are specified. Figure captions should be italicized. 

.. image:: /_static/images/mentor-center.jpg

.. figure:: /_static/images/peabody.jpg

   The first meeting of the first ever LaunchCode course, at Peabody Opera House in St. Louis in 2015

Bonus Mission
-------------

Headings with the text "Bonus Mission" should have a rocket icon inserted before the heading via CSS.

Since this utilizes the heading's automatically-generated `id` attribute, it won't work if there are multiple such headings on the same page.

Bonus Missions
--------------

Pluralizing the heading should work the same way.

Tables
------


Tables rows should alternate background color.

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

.. list-table:: List Table Title
   :header-rows: 1

   * - State
     - Abbreviation
     - Capital 
   * - Missouri
     - MO
     - Jefferson City
   * - Illinois
     - IL
     - Springfield
   * - Florida
     - FL
     - Tallahassee 

Code Blocks
-----------

Code block without higlighting, using ``::``:

::

   console.log("hello world");

Code block with JS highlighting:

.. sourcecode:: js

   function isPalindrome(str) {
      let reversed = str.split('').reverse().join('');
      return reversed === str;
   }

Code block with JS highlighting, with line numbers:

.. sourcecode:: js
   :linenos:

   class MyClass {

      constructor(arg) {
         this.prop = arg;
      }

   }

   let myVar = 42;
   
   // This is a comment
   function isPalindrome(str) {
      let reversed = str.split('').reverse().join('');
      return reversed === str;
   }

Make sure double-digit line numbers render properly

.. sourcecode:: js
   :linenos:

   function isPalindrome(str) {
      let reversed = str.split('').reverse().join('');
      return reversed === str;
   }






   function isPalindrome(str) {
      let reversed = str.split('').reverse().join('');
      return reversed === str;
   }


.. sourcecode:: css
   :linenos:

   .highlighttable .linenos {
      background-color: #eee;
      border-radius: 4px 0 0 4px;
      width: 42px;
      text-align: right;
   }


.. sourcecode:: html
   :linenos:

   <div>
      <p>Code block with JS highlighting:</p>
   </div>


.. admonition:: Example

   A code block within an admonition.

   .. sourcecode:: js
      :linenos:

      function isPalindrome(str) {
         let reversed = str.split('').reverse().join('');
         return reversed === str;
      }

.. admonition:: Example

   A code block with long lines should overflow properly.

   .. sourcecode:: html
      :linenos:
      
      <!doctype html>
      <head>
      </head>
      <body>

         <form id="searchForm">
            <input type="text" name="q" />
            <label><input type="radio" name="engine" value="google" />Google Google Google Google Google Google Google Google</label>
            <label>
                  <input type="radio" name="engine" value="duckduckgo" />
                  DuckDuckGo 
            </label>
            <label>
                  <input type="radio" name="engine" value="bing" />
                  Bing 
            </label>
            <label>
                  <input type="radio" name="engine" value="ask" />
                  Ask 
            </label>
            <input type="submit" value="Go!" />
         </form>

      </body>
