========
Images
========
 
---------------
Regular Images
---------------
 
Case veritus electram an pri, te modus tacimates volutpat usu, zril audiam ad qui. At ubique essent nec. Altera vituperata his ea, malis ocurreret ad vim. Eu ius patrioque gloriatur comprehensam, homero platonem ne nam. Timeam accumsan no nec, ei cum illud nostro laoreet, unum complectitur ad vis.
 
Note that with images, the image file must be relative to the source file. 
 
.. image:: images/compmanagement1.png
 
.. image:: images/properties1.png
 
 
-----------------------------------
Image that is also an External Link
-----------------------------------
 
The :code:`image` directive has the option :code:`target`. Click the cloud below to see where you go. 
 
.. image:: images/cloud.png
  :target: https://www.thestar.com/ 
 
 
Here is another method using substitution text:
 
The |biohazard|_ symbol must be used on containers used to dispose of medical waste. 
 
.. |biohazard| image:: images/biohazard.png 
.. _biohazard: http://docutils.sourceforge.net/rst.html
 
 
--------------------------------------------------
Image that is also an Internal Link to Other Page
--------------------------------------------------
 
The |biohazard1|_ symbol must be used on containers used to dispose of medical waste. 
 
.. |biohazard1| image:: images/biohazard2.png 
.. _biohazard1: Admonitions.html
 

 