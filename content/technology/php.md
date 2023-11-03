---
Title: PHP
Description: PHP overview
Template: technology
---
# PHP

PHP is a popular scripting language primarily used for creating websites with dynamic content. PHP is the most used server-side programming language on the web, with upwards of 80% of all websites using it.

PHP is an object-oriented programming language, which with later versions can be strictly typed and even JIT compiled.

A program that prints out all even numbers between 1 and 100 could look like the following in PHP:

```php
<?php
for ($i = 1; $i <= 100; $i++) {
    if (!($i % 2)) {
        print($i);
    }
}
```
