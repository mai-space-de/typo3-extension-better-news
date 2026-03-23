.. include:: /Includes.rst.txt

.. _introduction:

============
Introduction
============

**Maispace Better News** provides enhanced news rendering and configuration for TYPO3,
built on top of EXT:news. It ships ready-to-use TypoScript configuration sets and a
compatibility utility layer supporting both TYPO3 12.4 LTS and TYPO3 13.

Features
========

Configuration Sets
------------------

*  Ships a TYPO3 Site Set (``BetterNews``) with constants and setup TypoScript ready to
   include in any site package.
*  All configuration is scoped under the ``better_news`` extension key.

Compatibility Layer
-------------------

*  Includes a ``Compatibility`` utility class to handle differences between TYPO3 12.4
   and 13 in a single codebase.

Minimal Footprint
-----------------

*  No additional PHP dependencies beyond ``typo3/cms-core``.
*  Designed to be included in any TYPO3 project alongside EXT:news.
