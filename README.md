UCT_T Group Members List Extractor
==================================

UCT_T Group Members List Extractor is a simple application that allows an user to search through objects on the Novell Network Tree of the University of Cape Town (UCT) network via LDAP (Light-weight Directory Access Protocol) calls and extract lists from Novell Group objects, using a specified group filter.

Usage: UCT_T Group Members List Extractor.exe SEARCH_CONTEXT GROUP_OBJECT 
where SEARCH_CONTEXT is the tree context to search (e.g. ebe.main.uct); GROUP_OBJECT is the group (e.g. CF_ALLSTAFF_G) you wish to extract member names from. The * character acts like a wildcard character.

Created by Craig Lotter, May 2006

Note: This program is basically a updated version of Commerce Group Members List Extractor

*********************************

Project Details:

Coded in C# .NET using Visual Studio .NET 2005
Implements concepts such as LDAP programming and File manipulation.
Level of Complexity: Simple
