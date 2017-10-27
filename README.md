# A Ruby guide for PHP developers 📚

## Table of contents
- [Getting Started](#getting-started)
    - [Installation](#installation)
    - [Interactive Shell](#interactive-shell)

# Getting Started

## Installation

🐘 **PHP**:  
Installation instruction for each OS can be found on official PHP website
in the [Installing PHP guide](https://secure.php.net/manual/pt_BR/install.php).

You can confirm if the PHP was installed with success typing:
```bash
% php -v

PHP 7.1.3 (cli) (built: Mar 18 2017 19:23:29) ( NTS )
Copyright (c) 1997-2017 The PHP Group
Zend Engine v3.1.0, Copyright (c) 1998-2017 Zend Technologies
    with Xdebug v2.5.1, Copyright (c) 2002-2017, by Derick Rethans
```

💎 **Ruby**:  
Installation instruction for each OS can be found on official Ruby website
in the [Installing Ruby guide](https://www.ruby-lang.org/en/documentation/installation/).

You can confirm if the Ruby was installed with success typing:
```bash
% ruby -v

ruby 2.4.0p0 (2016-12-24 revision 57164) [x86_64-darwin16]
```

## Interactive Shell

Both languages come with an interactive shell.

🐘 **PHP**:  
```bash
% php -a

Interactive shell

php > echo "Hello World";
Hello World
```

💎 **Ruby**:  
```bash
% irb --simple-prompt
>> puts "Hello World"
Hello World
 => nil
```
❗️ *The flag `--simple-prompt` gives us a simpler prompt without the ruby version and line numbers.*
