freja — a theme for Sphinx document generator
=============================================

This is a simple and (hopefully) clean theme for Sphinx_. 
You can see it used `here <https://dmitriid.github.io/xstream4j/xstream4j/Stream.html>`_.
Or see screenshots at the bottom of this page.

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
- Support for project logo (set in your conf.py and add image to ``_static``) 
- All within one file

**It does not provide**

- Full featured support for everything Sphinx has to offer (I don't know what that may be though :) )
- Extensibility (yet?). It does not inherit from basic theme's layout and does not provide blocks itself
- i18n for hardcoded strings. Once again, not realy using all of Sphinx's features

Acknowledgements
================

Version 0.2 is based on `Elixir docs <http://elixir-lang.org/docs/stable/elixir/Kernel.html>`_.

`Linear Icons <https://linearicons.com/free>`_ licensed under `CC BY-SA 4.0 <https://creativecommons.org/licenses/by-sa/4.0/>`_.


What it looks like
==================

Version 0.2
-----------

.. image:: http://dmitriid.com/i/gm2tonzzgqydknjv.png
   :width: 800px

.. image:: http://dmitriid.com/i/gm2toobtgmztonzs.png
   :width: 800px


Version 0.1
-----------

.. image:: http://dmitriid.com/i/gm2tomjxhaydcnrv.png
   :width: 800px

.. _Sphinx: http://www.sphinx-doc.org/
.. _templating: http://www.sphinx-doc.org/en/stable/templating.html#jinja-sphinx-templating-primer

