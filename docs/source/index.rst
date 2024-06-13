.. EEWiki Demo documentation master file, created by
   sphinx-quickstart on Tue Jun 11 19:15:59 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. index:: needs

Welcome to My Wiki!
=======================================
This is a demo wiki for the EEWiki project. The aim of the project is to create a wiki that can be used by students to learn about various topics in Electrical Engineering. The wiki will be created by students for students.

Table of Contents
-----------------

.. toctree::
   :maxdepth: 2
   :caption: Topics:

   Topics/EntityRelationshipDiagrams
   Topics/RelationalAlgebra
   Topics/SQL

Node Graph
----------

This is a simple visualisation of the structure of the wiki. It demonstrates how interconnected the different pages on the wiki are. Click on the nodes to navigate to the corresponding pages.

.. raw:: html

   <div style="text-align: center; margin: 20px 0;">

.. mermaid::

   graph TD
     A[Home Page] --> B[ERD]
     A --> C[Relational Algebra]
     A --> D[SQL]
     B --> E[Subpage1]
     C --> F[Subpage2]

   click A "index.html"
   click B "Topics/EntityRelationshipDiagram.html"
   click C "Topics/RelationalAlgebra.html"
   click D "Topics/SQL.html"
   click E "Topics/subpage1.html"
   click F "Topics/subpage2.html"

.. raw:: html

   </div>
