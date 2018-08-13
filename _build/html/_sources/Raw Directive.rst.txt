==============
Raw Directive
==============

The "raw" directive allows reST text to be bypassed. The example below is the HTML code to open an external link in a separate window::

  You can |green|.

  .. |green| raw:: html
  
  <a href="http://geoiptool.com" target="_blank">check your location here</a>.

 turns into this:

 You can |green|.

 .. |green| raw:: html

  <a href="http://geoiptool.com" target="_blank">check your location here</a>.

But you shouldn't overuse or abuse this directive because it's a potential security hole or something. `Click here`_ for more info.

.. _Click here: http://docutils.sourceforge.net/docs/ref/rst/directives/html#raw-data-pass-through

