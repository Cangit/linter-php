# linter-php+

This package will lint your `.php` opened filed in Atom through [php -l](http://www.php.net/manual/en/features.commandline.options.php).

## Installation

* Install [php](http://php.net).
* `$ apm install linter` (if you don't have [AtomLinter/Linter](https://github.com/AtomLinter/Linter) installed).
* `$ apm install linter-php`

## Settings
You can configure linter-php by editing ~/.atom/config.cson (choose Open Your Config in Atom menu):
```
'linter-php':
  'phpExecutablePath': null # php path. run 'which php' to find the path
```
## Other available linters
- [linter-phpcs](https://atom.io/packages/linter-phpcs) - Linter plugin for PHP, using phpcs.
- [linter-phpmd](https://atom.io/packages/linter-phpmd) - Linter plugin for PHP, using phpmd.
- [linter-php](https://atom.io/packages/linter-php) - The linter plugin this one is forked from

## Forked with <3
This is a fork from [linter-php](https://atom.io/packages/linter-php). Containing the latest pull requests and no deprecation warnings.
