freja — a theme for Sphinx document generator
=============================================

This is a simple and (hopefully) clean theme for Sphinx_.
You can see it used `here <https://dmitriid.github.io/xstream4j/xstream4j/Stream.html>`_.
Or see screenshot below.

How to
======

One of:

- `download <https://github.com/dmitriid/freja-sphinx/releases>`_ a release and extract it to your Sphinx doc directory.
- ``git clone`` this repo and copy ``freja/_static`` and ``freja/_templates`` to your Sphinx doc directory. 

See templating_ for more info. The relevant bits:

   To customize the output of your documentation you can **override all the templates** 
   (both the layout templates and the child templates) **by adding files with the same name**
   as the original filename **into the template directory** of the structure the Sphinx quickstart 
   generated for you.
  
   Sphinx will look for templates in the folders of templates_path first, and if it can’t find 
   the template it’s looking for there, it falls back to the selected theme’s templates.

Thus the ``_templates/layout.html``.

What
====

This theme/layout override might not provide all the bells and whistles of a full-blown theme. 

**It provides**:

- An overall layout
- ToC for current page
- ToC for overall docs
- Support for class/method/params/fields
- Support for index pages
- Support for the search page
- All within one file

**It does not provide**

- Full featured support for everything Sphinx has to offer (I don't know what that may be though :) )
- Extensibility (yet?). It does not inherit from basic theme's layout and does not provide blocks itself
- i18n for hardcoded strings. Once again, not realy using all of Sphinx's features

Acknowledgements
================

`Bulma <http://bulma.io/documentation/layout/footer/>`_ by `Jeremy Thomas <http://jgthms.com>`_. 
The source code is licensed `MIT <http://opensource.org/licenses/mit-license.php>`_.

`Typeplate <http://typeplate.com>`_ by Dennis Gaebel
(`@gryghostvisuals <https://twitter.com/gryghostvisuals>`_) &
Zachary Kain (`@zakkain <https://twitter.com/@zakkain>`_).
The source code is licensed `CC BY 3.0 <hhttps://creativecommons.org/licenses/by/3.0/us/>`_.


What it looks like
==================

.. image:: http://dmitriid.com/i/gm2tomjxhaydcnrv.png
   :width: 800px

.. _Sphinx: http://www.sphinx-doc.org/
.. _templating: http://www.sphinx-doc.org/en/stable/templating.html#jinja-sphinx-templating-primer

