
Title : matplotlib: past, present and future
============================================

Authors :
----------

- Michael Droettboom

Track :
-------

Reproducible Science

Abstract :
----------
This talk will be a general "state of the project address" for matplotlib, the
popular plotting library in the scientific Python stack. It will provide an
update about new features added to matplotlib over the course of the last year,
outline some ongoing planned work, and describe some challenges to move into the
future. The new features include a web browser backend, "sketch" style, and
numerous other bugfixes and improvements. Also discussed will be the challenges
and lessons learned moving to Python 3. Our new "MEP" (matplotlib enhancement
proposal) method will be introduced, and the ongoing MEPs will be discussed,
such as moving to properties, updating the docstrings, etc. Some of the more
pie-in-the-sky plans (such as styling and serializing) will be discussed. It is
hoped that this overview will be useful for those who use matplotlib, but don't
necessarily follow its mailing list in detail, and also serve as a call to arms
for assistance for the project.


Title : astropy: bringing astronomical tools down to earth
==========================================================

Authors :
----------

- Michael Droettboom
- Nadia Dencheva
- Tom Aldcroft

Track :
-------

General

Abstract :
----------
In the process of developing the core tools in astropy, some modules
have been developed that have wider applicability than just for
astronomy. This talk will describe these tools and the approach taken
by astropy towards these. These include general tools for handling
units, and quantities with units, with capabilities not found in other
unit packages, such as equivalency mappings. We have also developed a
generic system for defining models and interfacing models with generic
fitting algorithms in an easily extensible way. This system underlies
our approach for mapping array coordinates to general world coordinate
systems. Finally, a powerful table interface has been developed that
handles many different data formats (currently focused mostly on
astronomical varieties, but extensible to other fields as well).
