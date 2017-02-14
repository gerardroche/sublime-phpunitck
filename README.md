# WHAT PHPUNIT COMPLETIONS IS

[![Minimum Sublime Version](https://img.shields.io/badge/sublime-%3E%3D%203.0-brightgreen.svg?style=flat-square)](https://sublimetext.com) [![Latest Stable Version](https://img.shields.io/github/tag/gerardroche/sublime-phpunit-completions.svg?style=flat-square&label=stable)](https://github.com/gerardroche/sublime-phpunit-completions/tags) [![GitHub stars](https://img.shields.io/github/stars/gerardroche/sublime-phpunit-completions.svg?style=flat-square)](https://github.com/gerardroche/sublime-phpunit-completions/stargazers) [![Author](https://img.shields.io/badge/twitter-gerardroche-blue.svg?style=flat-square)](https://twitter.com/gerardroche)

PHPUnit completions for Sublime Text.

## OVERVIEW

* [Features](#features)
* [Key Bindings](#key-bindings)
* [Installation](#installation)
* [Contributing](#contributing)
* [Changelog](#changelog)
* [License](#license)

## FEATURES

* PHPUnit ~5.4
* DbUnit ~2.0
* [PSR](http://www.php-fig.org) compliant
* Scoped to minimise auto-complete noise
* Test case type hints e.g. begin typing at `class Name extends |` and any other context where a type hint is valid.
* Assertions e.g. begin typing `assert|` or `$this->assert|`
* Test case helpers e.g. begin typing `getMockBuilder|` or `$this->getMockBuilder|`
* Annotations e.g. begin typing _(any valid doc block scope)_ `/* @covers| */` or without the `@` symbol `/* covers| */`

## KEY BINDINGS

| OS X | Windows | Linux | Description |
|------|---------|-------|-------------|
| <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Alt</kbd>+<kbd>/</kbd> | Activate completions |

To enable [tab-completions](http://docs.sublimetext.info/en/latest/extensibility/completions.html#tab-completed-completions) set `"tab_completion": true` in `Preferences > Settings - User`.

## INSTALLATION

### Manual installation

1. Close Sublime Text.
2. Download or clone this repository to a directory named **`phpunit-completions`** in the Sublime Text Packages directory for your platform:
    * Linux: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/.config/sublime-text-3/Packages/phpunit-completions`
    * OS X: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/phpunit-completions`
    * Windows: `git clone https://github.com/gerardroche/sublime-phpunit-completions.git %APPDATA%\Sublime/ Text/ 3/Packages/phpunit-completions`
3. Done!

## CONTRIBUTING

Your issue reports and pull requests are always welcome.

## CHANGELOG

See [CHANGELOG.md](CHANGELOG.md).

## LICENSE

Released under the [BSD 3-Clause License](LICENSE).
