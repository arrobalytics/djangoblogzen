.. figure:: zinnia/static/zinnia/logo/dbz_logo_text.png
    :scale: 50
    :align: center


This project is a friendly fork of the `original Django Blog Zinnia`_ project by Julien Fache `@Fantomas42`_.

Despite multiple attempts to contact `Julien Fache`_, the original Zinnia repository
is no longer active and maintained by its author. Virtually no activity since March 2020
has been recorded, and the project is no longer compatible with modern versions of Django 3 & 4.\

In order to recover the project's legacy, and to provide a community maintained
alternative, this fork this has been created.\

Please head over to `Docs.DjangoBlogZinnia.com`_ for documentation and
other resources.\

Installation
============

Using pip:

``pip install git+https://github.com/arrobalytics/django-blog-zinnia.git@v0.22-alpha4``.

Using pipenv, add Django Blog Zinnia to your Pipfile dependencies:

``django-blog-zinnia = { git = "https://github.com/arrobalytics/django-blog-zinnia.git@v0.22-alpha3" }``

Then run:

``pipenv install``


RoadMap
=======

As a priority, this fork will be focused on updating Zinnia to work with modern versions of Django and
in removing/replacing all deprecated features.

Once the project is updated, the following activities are planned for future releases:

* Inspection, evaluation and update of Zinnia's dependencies.
* Extension of Entry Model to create and support multiple image sizes for SEO and performance purposes.
* Implementation of a browser-based Entry editor to eliminate the need to write plain Markdown on the Django Admin site for creating Entries.
* Develop a new Zinnia default theme based on modern CSS frameworks such as Bulma, Bootstrap, etc.
* Update Tests and make use of GitHub actions for testing.
* Update documentation.

===================================
Django Blog Zinnia
===================================

Simple yet powerful and really extendable application for managing a blog within your Django Web site.

Django Blog Zinnia is a community maintained fork of the abandoned Django Blog Zinnia project by `@Fantomas42`_.
Zinnia has been made for publishing Weblog entries and designed to do it well.

Basically any feature that can be provided by another reusable app has been left out.
Why should we re-implement something that is already done and reviewed by others and tested?

Features
========

More than a long speech, here the list of the main features:

* Comments
* `Sitemaps`_
* Archives views
* Related entries
* Private entries
* RSS or Atom Feeds
* Tags and categories views
* `Advanced search engine`_
* Prepublication and expiration
* `Custom templates for various contents`_
* Editing in `Markdown`_, `Textile`_ or `reStructuredText`_
* Widgets (Popular entries, Similar entries, ...)
* Spam protection with `Akismet`_, `TypePad`_ or `Mollom`_
* Admin dashboard
* `MetaWeblog API`_
* Ping Directories
* Ping External links
* `Bit.ly`_ support
* `Twitter`_ support
* `Gravatar`_ support
* `Django-CMS`_ plugins
* Collaborative work
* Tags autocompletion
* `Entry model extendable`_
* Pingback/Trackback support
* `Blogger conversion utility`_
* `WordPress conversion utility`_
* `WYMeditor`_, `TinyMCE`_ , `CKEditor`_ and `MarkItUp`_ support
* Efficient database queries
* Ready to use and extendable templates
* `Compass`_ and `Sass3`_ integration
* `Windows Live Writer`_ compatibility




Examples
========

Take a look at the online demo at: http://demo.djangoblogzinnia.com/
or you can visit these websites who use Zinnia.

* `Fantomas' side`_
* `Vidzor Studio LLC`_
* `Bookshadow`_
* `Future Proof Games`_
* `Programeria`_
* `Tihomir Blajev Blog`_
* `Branchspot`_

If you are a proud user of Zinnia, send me the URL of your website and I
will add it to the list.

Online resources
================

More information and help available at these URLs:

* `Code repository`_
* `Documentation`_
* `Travis CI server`_
* `Coverage report`_
* Discussions and help at `Google Group`_
* For reporting a bug use `GitHub Issues`_

.. |travis-develop| image:: https://img.shields.io/travis/Fantomas42/django-blog-zinnia/develop.svg
   :alt: Build Status - develop branch
   :target: http://travis-ci.org/Fantomas42/django-blog-zinnia
.. |coverage-develop| image:: https://img.shields.io/coveralls/Fantomas42/django-blog-zinnia/develop.svg
   :alt: Coverage of the code
   :target: https://coveralls.io/r/Fantomas42/django-blog-zinnia
.. |latest-version| image:: https://img.shields.io/pypi/v/django-blog-zinnia.svg
   :alt: Latest version on Pypi
   :target: https://pypi.python.org/pypi/django-blog-zinnia/
.. |paypal| image:: https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif
   :alt:  Make a free donation with Paypal to encourage the development
   :target: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=68T48HR8KK9KG

.. _`Sitemaps`: http://docs.djangoblogzinnia.com/en/latest/getting-started/configuration.html#module-zinnia.sitemaps
.. _`Advanced search engine`: http://docs.djangoblogzinnia.com/en/latest/topics/search_engines.html
.. _`Custom templates for various contents`: http://docs.djangoblogzinnia.com/en/latest/getting-started/configuration.html#templates-for-entries
.. _`Markdown`: http://daringfireball.net/projects/markdown/
.. _`Textile`: http://redcloth.org/hobix.com/textile/
.. _`reStructuredText`: http://docutils.sourceforge.net/rst.html
.. _`Akismet`: https://github.com/Fantomas42/zinnia-spam-checker-akismet
.. _`TypePad`: https://github.com/Fantomas42/zinnia-spam-checker-akismet#using-typepad-antispam
.. _`Mollom`: https://github.com/Fantomas42/zinnia-spam-checker-mollom
.. _`MetaWeblog API`: http://www.xmlrpc.com/metaWeblogApi
.. _`Bit.ly`: https://github.com/Fantomas42/zinnia-url-shortener-bitly
.. _`Twitter`:  https://github.com/Fantomas42/zinnia-twitter
.. _`Gravatar`: http://gravatar.com/
.. _`Django-CMS`: http://docs.djangoblogzinnia.com/en/latest/getting-started/configuration.html#django-cms
.. _`Entry model extendable`: http://django-blog-zinnia.rtfd.org/extending-entry
.. _`WYMeditor`: https://github.com/django-blog-zinnia/zinnia-wysiwyg-wymeditor
.. _`TinyMCE`: https://github.com/django-blog-zinnia/zinnia-wysiwyg-tinymce
.. _`CKEditor`: https://github.com/django-blog-zinnia/zinnia-wysiwyg-ckeditor
.. _`MarkItUp`: https://github.com/django-blog-zinnia/zinnia-wysiwyg-markitup
.. _`Blogger conversion utility`: https://github.com/django-blog-zinnia/blogger2zinnia
.. _`WordPress conversion utility`: https://github.com/django-blog-zinnia/wordpress2zinnia
.. _`Compass`: http://compass-style.org/
.. _`Sass3`: http://sass-lang.com/
.. _`Windows Live Writer`: http://explore.live.com/windows-live-writer
.. _`Fantomas' side`: http://fantomas.site/blog/
.. _`Vidzor Studio LLC`: http://vidzor.com/blog/
.. _`Bookshadow`: http://bookshadow.com/weblog/
.. _`Future Proof Games`: http://futureproofgames.com/blog/
.. _`Programeria`: https://programeria.pl/
.. _`Tihomir Blajev Blog`: http://www.tihoblajev.com/weblog/
.. _`Branchspot`: https://www.branchspot.com/blog/
.. _`Code repository`: https://github.com/arrobalytics/django-blog-zinnia
.. _`Documentation`: http://docs.djangoblogzinnia.com/
.. _`Travis CI server`: http://travis-ci.org/Fantomas42/django-blog-zinnia
.. _`Coverage report`: https://coveralls.io/r/Fantomas42/django-blog-zinnia
.. _`Google Group`: http://groups.google.com/group/django-blog-zinnia/
.. _`GitHub Issues`: https://github.com/arrobalytics/django-blog-zinnia/issues/
.. _`original Django Blog Zinnia`: https://github.com/Fantomas42/django-blog-zinnia/
.. _`@Fantomas42`: https://github.com/Fantomas42/
.. _`Julien Fache`: https://github.com/Fantomas42/
.. _`Docs.DjangoBlogZinnia.com`: https://docs.djangoblogzinnia.com
