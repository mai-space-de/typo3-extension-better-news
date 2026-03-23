.. include:: /Includes.rst.txt

.. _installation:

============
Installation
============

Requirements
============

*  PHP 8.2 or later
*  TYPO3 CMS 12.4 LTS or 13.x LTS
*  Composer (recommended)
*  EXT:news installed and configured

Composer Installation
=====================

Run the following command in your TYPO3 project root:

.. code-block:: bash

    composer require maispace/better-news

Activate the Extension
======================

The extension is activated automatically when installed via Composer. If you manage
extensions via the TYPO3 backend, activate ``better_news`` in the **Extension Manager**.

Include Configuration Set
=========================

Add the ``BetterNews`` configuration set to your site's configuration in
``config/sites/<site-identifier>/config.yaml``:

.. code-block:: yaml

    sets:
      - better_news/BetterNews

Alternatively, include the TypoScript manually in your root TypoScript template:

.. code-block:: typoscript

    @import 'EXT:better_news/Configuration/Sets/BetterNews/setup.typoscript'
