Node Graph
==========

.. mermaid::

   graph TD
     A[Home] --> B[[Page1]]
     A --> C[[Page2]]
     B --> D[[Subpage1]]
     C --> E[[Subpage2]]

   click A "index.html"
   click B "Databases.html"
   click C "SQL.html"
   click D "subpage1.html"
   click E "subpage2.html"
