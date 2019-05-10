# MarcEdit-Plugins
Library software plugin code for popular MarcEdit (by Terry Reese) work with Innovative Interfaces Sierra System

MarcEdit is fully featured .NET software system written by Terry Reese. Primarily it is used for viewing and editing MARC21
Bibliographic records for library collections.

MarcEdit allows for customization of its functions via plugin code written in .NET and conforming to the appropriate Interface.
This repository holds various .dll and .exe files that either function as plugins or stand alone utility programs.

This project was started in 2009 and is currently used by a handful of public libraries in western Colorado belonging to the Marmot.org
consortium. These libraries all share a union catalog which is the Innovative Interfaces Sierra System. The primary function of the
project is to add a 9xx series field to each bib record in a file of records that links to an order record in the Sierra database. 
This addition results in a better record loading process and helps to avoid duplicate entries in the database, a common source of 
frustration in the cataloging world.

Additional functions have been added including customization of MarcEdit's user interface and the creation of various external documents
that are helpful in our materials processing workflow, namely creating spine labels and an MS Word schedule of processing steps for each
item processed.

Finally the plugin also implements a set of extremely site specific rules governing the modification of so called '949' fields that
contain the item specifics to create item records in the Sierra database as the Bibliographic records are loaded. These modifications
are primarily to the CALL NUMBER, LOCATION and ITYPE fields.
