=============
Tables
=============
 
.. table:: **Table Green**
   :widths: grid
   :align: center
 
   =====  =====
     A    not A
   =====  =====
   False  True
   True   False
   =====  =====
 
.. |br| raw:: html
 
   <br />
 
 
|br|
|br|
|br|
 
.. list-table:: **To View!**
   :widths: 15 10 30
   :header-rows: 1
 
   * - Treat
     - Quantity
     - Description
   * - Albatross
     - 2.99
     - On a stick!
   * - Crunchy Frog
     - 1.49
     - If we took the bones out, it wouldn't be
       crunchy, now would it?
   * - Gannet Ripple
     - 1.99
     - On a stick!
 
|br|
|br|
|br|
 
======= ======================= ==============================================
Verb    URL                     Action
======= ======================= ==============================================
POST    /folder                 Creates a new document within the folder
GET     /folder/{document-id}   Request the current state of the document
PATCH   /folder/{document-id}   Update the document details
DELETE  /folder/{document-id}   Remove the document
======= ======================= ==============================================
