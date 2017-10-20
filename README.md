# A Ruby guide for PHP developers

## Table of contents
- [Getting Started](#getting-started)
    - [Hello World](#hello-world)
- [Language Reference](#language-reference)
  - [Comments](#comments)
  - [Variables](#variables)
  - [Constants](#constants)

## Getting Started

## Hello World

**PHP**:
```php
<?php

echo "Hello World";
```

**Ruby**:
```php
puts "Hello World"
```

## Language Reference

## Comments

**PHP**:
```php
// One line comment

/*
Multi
line
comments
*/
```

**Ruby**:  
There is not multi-line comment in ruby.
```ruby
# One line comment
```

## Variables
Both languages are dynamic typed, which means we must not set the variable
type. The type is always infered when you set a value to it, and you can change
the valye type anytime, without to care about type casts.

**PHP**:  
All PHP variables must start with dollar sign($).
```php
$message = "Hello World";
```

**Ruby**:
```ruby
message = "Hello World"
```

## Constants

**PHP**:  
There're two ways to define a constant in PHP.
```php
/**
 * The define function accept two parameters, the first one is the name of the
 * constant(Usually defined in uppercase), and the second one is the value.
 *
 * This definition doesn't works inside a class definition.
 */
define('VERSION', '1.0.2');

/**
 * Using the const keyword you'll be able to declare constants inside and outside
 * of a class definition.
 */
const ENVIROMENT = 'development';
```

**Ruby**:
```ruby
VERSION = '1.0.2'
```
