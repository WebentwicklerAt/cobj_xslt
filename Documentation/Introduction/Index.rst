﻿.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../Includes.txt


Introduction
------------

What does it do?
^^^^^^^^^^^^^^^^

This extension adds a new content object XSLT to the standard
TypoScript cObjects. With the XSLT cObject you can retrieve and
transform XML data with pure TypoScript and XSL stylesheets.
The data can be fetched from database fields, files or external
resources.

Features
^^^^^^^^

- TypoScript based approach to XML processing with XSLT

- Works with database fields, files or external XML & XSL resources

- XML can be 'piped' through multiple XSL transformations

- Register PHP functions for use in your XSL stylesheets

- Call cObjects in your XSL stylesheets using 'typoscriptObjectPath'

- Set and remove XSLT parameters with stdWrap

- Each XSL transformation can also be written to a file

- Debug errors and get profiling information in the TSFE admin panel

Other interesting use cases
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Many ideas come to mind where you could make use of the XSLT
object. Here are some:

- Transform flexform content. Might come in handy if you use `Templavoila <http://typo3.org/extensions/repository/view/templavoila/current/>`_ , `FLUX <http://typo3.org/extensions/repository/view/flux/current/>`_ or
  any other XML based content format.

- Access and display XML content provided over REST APIs on your TYPO3
  website.

- Display lists of publications based on XML exports from citation managers
  on your website (as has been done in `this nice example
  <https://www.rhrk.uni-kl.de/internetdienste/wwwdienste/webauftritt/citavi-import-howto/>`_)

- Use it together with the `XPATH content object <http://typo3.org/extensions/repository/view/cobj-xpath>`_
  to select and then transform chunks of XML structures.

- Store your TYPO3 content as XML files, for example by defining another pagetype that outputs
  XML which is then written to disk with the XSLTs transformToURI property.

And much more...

Credits
^^^^^^^

This TYPO3 extension has been developed within the context of the `Digital Humanities
<http://www.digitale-akademie.de/projekte/matrix.html>`_ projects
of the `Digital Academy Mainz <http://www.digitale-akademie.de/>`_.