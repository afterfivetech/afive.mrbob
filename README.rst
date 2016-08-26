.. This README is meant for consumption by humans and pypi. Pypi can render rst files so please do not use Sphinx features.
   If you want to learn more about writing documentation, please check out: http://docs.plone.org/about/documentation_styleguide.html
   This text does not appear on pypi or github. It is a comment.

==============================================================================
Afive.mrbob
==============================================================================

Afive.mrbob is a module for creating official and Afive-specific Plone 5 packages 

Features
--------

- Downloads and installs Mrbob with official and Afive specific templates


Installation
------------

- Clone source code using git::

  git clone https://github.com/afterfivetech/afive.mrbob.git

- Initialize buildout::

  cd afive.mrbob
  path/to/virtualenv/bin/python bootstrap.py

- Run buildout::

  ./bin/buildout

This will create bin/mrbob, the script to run when you want to create Plone 5 packages


Use
---

- Run Mrbob as follows::

  path/to/afive.mrbob/bin/mrbob -O package.name bobtemplates:plone_addon

- Answer all questions asked by the script

- Initialize new package::

  cd package.name
  path/to/virtualenv/bin/python buildout-bootstrap.py 

- Buildout new package (installs Plone and other required modules)::

  ./bin/buildout
