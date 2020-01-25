Sublime-GenericConfig
=====================

Sublime-GenericConfig adds syntax highlighting of the configuration files
to Sublime Text 2 and Sublime Text 3.

It aims to provide generic highlighting for files which are
not supported by other plugins (for example ini files, nginx config).

This plugin may be used for a wide range of configuration files
because highlighting is based on common syntax constructions.

*NOTE*: `0.0.6` is last version for Sublime Text 2.

Supported constructions
-----------------------

* One line comments (`#`, `//`, `--` and `;`)
* Block comments (`/* ... */`)
* Numbers, hex values, numbers with units (`12M`, `10kHz` etc)
* Color (`#ccc`, `#12ccff` etc)
* Common constants (`true`/`false`, `yes`/`no` etc)
* Strings (single quotes and double quoted)
* Sections (`[name]`, `<name>`, `name { ... }`)
* Key-value constructions (`key = value`, `key: value`, `key value ...`)
* Variables (`$name`, `%name`, `%name%`, `${name}` and few others)
* Uppercase names (`SOME_NAME`)
* URL-like strings (`http://name.org`, `some://name:port/path`)
* RegEx-like strings (`^...$`)
* Common operators (`+`, `-` etc)
* Mime-like strings (`image/gif`, `multipart/form-data` etc)
* Function call (`name()`)
