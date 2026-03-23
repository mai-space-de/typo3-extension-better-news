# maispace/better-news — TYPO3 Better News

[![CI](https://github.com/mai-space-de/typo3-extension-better-news/actions/workflows/ci.yml/badge.svg)](https://github.com/mai-space-de/typo3-extension-better-news/actions/workflows/ci.yml)
[![PHP](https://img.shields.io/badge/PHP-8.2%2B-blue)](https://www.php.net/)
[![TYPO3](https://img.shields.io/badge/TYPO3-12.4%20%7C%7C%2013-orange)](https://typo3.org/)
[![License](https://img.shields.io/badge/License-GPL--2.0--or--later-green)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)

Enhanced news rendering and configuration for TYPO3, built on EXT:news.

---

## ✨ Features

- Enhanced TypoScript configuration for EXT:news
- Compatibility layer for TYPO3 12.4 and 13
- Ready-to-use configuration sets via TYPO3 Site Sets

## 📦 Installation

```bash
composer require maispace/better-news
```

Activate the extension in the TYPO3 Extension Manager, then include the provided
configuration set in your site package.

## 🔧 Development

```bash
# Install dependencies
composer install

# Check all linters
composer lint:check

# Auto-fix code style
composer lint:fix

# Run unit tests
composer test:unit

# Run PHPStan analysis
composer check:phpstan
```

## 📄 License

This extension is published under the [GNU General Public License v2.0 or later](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).

