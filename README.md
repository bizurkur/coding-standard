# Coding Standard

Bizurkur coding standard for [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer). This heavily uses most of the [Slevomat standard](https://github.com/slevomat/coding-standard), with the addition of some others.

## Installation

It's best to install using [Composer](https://getcomposer.org/).

```sh
$ composer require bizurkur/coding-standard
```

## Usage

In your phpcs.xml.dist file, add a rule:

```xml
<?xml version="1.0"?>
<ruleset name="AcmeProject">
	<rule ref="vendor/bizurkur/coding-standard/ruleset.xml">
		<!-- sniffs to exclude -->
	</rule>
</ruleset>
```

Or via the command line:

```sh
vendor/bin/phpcs --standard=vendor/bizurkur/coding-standard/ruleset.xml
```
