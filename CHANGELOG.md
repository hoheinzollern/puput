Changelog
=========

Unreleased
----------


2.2.0 (2025-04-07)
------------------
* Add Wagtail 6.2 and 6.3 support.
* EntryPage: auto slug generation from title
* Upgrade django-taggit >=5.0,<6.2
 
2.1.1 (2024-06-25)
------------------
* Update docs
 
2.1.0 (2024-06-14)
------------------
* Add Wagtail 6.1 support. Drop Wagtail <=5.2 support.
* Add Django 5.0 support.

2.0.0 (2023-07-04)
------------------
* Add Wagtail 5.0 support. Drop Wagtail <=4.0 support.
* Add Django 4.2 support.
* Upgrade jQuery to 2.2.4

1.2.1 (2023-05-16)
------------------
* Add Python 3.11 support. Drop Python <=3.7 support.
* Add Django 4 support. Drop Django <3.2 support.
* Apply black.
* Update tox.
* Add markdown to EntryPages.

1.2.0 (2022-12-16)
------------------
* Add Wagtail 4 support. Drop Wagtail <3 support.
* Drop Django <2.2 support.
* Update requirements-test.
* Update tox.
* Fix: include Python 3.10 on setup classifiers.

1.1.4 (2022-12-14)
------------------
* Add Wagtail 3 support.
* Add Python 3.10 support. Drop Python 3.6 support.
* Remove travis.
* Fix tests suite and apply flake8.
* Updated some docs.

1.1.3 (2021-11-05)
------------------
* Add Django 3.2 support. Drop Django <2.2 support.
* Add Wagtail 2.10-2.14 support.
* Add Python 3.9 to travis test matrix.
* Updated some docs.
* Fix circular imports.

1.1.1 (2020-06-13)
------------------
* Add Django 3.0 support. Drop Python 3.5 support.
* Add Wagtail 2.9 support.
* Show authorship on entry page without image.
* Fix duplicate pages on sitemap.

1.1.0 (2020-03-16)
------------------
* Updated blog model to be extensible
* Add possibility of introducing new comment providers

1.0.7 (2020-03-01)
------------------
* Fix `puput_initial_data` command.

1.0.6 (2019-12-01)
------------------
* Add support for Wagtail >2.7.
* Add Python 3.7 and 3.8 to travis test matrix.

1.0.5 (2019-09-03)
------------------
* Add support for Wagtail 2.6.
* Remove Python 2 compatibility code.
* Fix header image in related entries.
* Remove Google Plus share buttons.

1.0.4 (2019-05-27)
------------------
* Add support for Wagtail 2.4.
* Update Django version to greater than 2.1.6 to fix security issues.
* Updated some docs.
* Fix entry header image.
* Adding EntryAbstract.content_panels.

1.0.3 (2018-12-13)
------------------
* Updated some docs.
* Fixing social share urls to match `entry_url` (Thanks to @misraX).
* Django URLS upgrading to 2.0 and Wagtail 2.3 support (Thanks to @MiltonLn)
* Adding support for Django 2.1 and Wagtail 2.3 patch versions (Thanks to @MiltonLn)
* Arabic translation (Thanks to @ahwebd)

1.0.2 (2018-05-17)
------------------
* Add missing image.
* Add missing `str` methods.

1.0.1 (2018-04-19)
------------------
* Fix header image.

1.0 (2018-04-10)
------------------
* Add support for Django 2.0 and Wagtail 2.0. Drop Python 2.7 support.
* Add code and block quote options to the entries text editor.
* Improve default template visualisation.
* Configurable default template color.
* Add social sharing links.

0.9.2 (2018-02-13)
------------------
* Remove django-compressor dependency.
* Add German and Polish translations.

0.9.1 (2017-09-12)
------------------
* Add missing migration.

0.9 (2017-08-03)
----------------
* Fix issue that creates undesired migrations.
* Add Django 1.11 & Python 3.6 support. Drop Python 3.3 support
* Improve RSS feeds generation.
* Fix issue with templatetags.
* Add Italian, Russian, Brazilian and French translations.
* Fix url resolution issues.

0.8 (2016-11-17)
----------------
* Add Travis CI integration and functional tests.
* Add Django 1.10 support.
* Minor template tweaks.

0.7 (2016-08-18)
------------------
* Add initial travis support.
* Add canonical url and social share tags in templates for SEO purposes.
* Allow to place Puput's blog at any sitemap level.
* Fix issue in entry comments update method.
* Add PageChooserPanel for related entries chooser.
* Improve flexibility on adding other comment systems.
* Minor bug fixes.

0.6 (2016-05-18)
------------------
* Fix issue when displaying entries without images.
* Fix css issues.
* Add django-compressor as project dependency.
* Improve tags visualization.

0.5.2 (2016-02-18)
------------------
* Removed django-endless-pagination which is no longer maintained and is not compatible with Django 1.9. Replaced by django-el-pagination.
* Category slug is now editable on snippets section.

0.5.1 (2016-02-16)
------------------
* Fix bug due a missing template tag.

0.5 (2016-02-12)
------------------
* Altered URL structure in order to have blog as Wagtail root page.
* Added Docker integration.
* Archive list is now collapsible.

0.4.1 (2016-01-19)
------------------
* Minor css bug fixes.

0.4 (2015-12-09)
----------------
* Added a fancy logo.
* Improved visualization of entries header images.
* Minor bug fixes.


0.3 (2015-11-15)
----------------
* Customizable username field in settings file.
* Improvements in the documentation.
* CSS cleanup. Added LESS file.
* Minor bug fixes.
* Added catalan translations.

0.2 (2015-09-22)
----------------
* Extensible entry model.

0.1 (2015-09-12)
----------------
* Initial release.
