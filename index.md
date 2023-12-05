# PHP to Moodle feature availability summary

This is a summary of features I use frequently and need to check.

This is not intended to be an exhaustive list, but if you'd like to add to it, please submit a PR.

| PHP | 7.2 | 7.3 | 7.4 | 8.0 | 8.1 | 8.2 | 8.3 | 8.4 |
| ---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Moodle 3.9 | x | x | x |
| Moodle 3.10 | x | x | x |
| Moodle 3.11 | | x | x | x |
| Moodle 4.0 | | x | x | x |
| Moodle 4.1 | | | x | x | x |
| Moodle 4.1 | | | | x | x | x |
| Moodle 4.2 | | | | x | x | x |
| Moodle 4.3 | | | | x | x | x | x |
| Moodle dev | | | |  | x | x | x | x |
| PHP | 7.2 | 7.3 | 7.4 | 8.0 | 8.1 | 8.2 | 8.3 | 8.4 |
| [Type Declarations](https://stitcher.io/blog/typed-properties-in-php-74) |
| Typed properties | | | x | x | x | x | x | x | x | x|
| Union types | | | | x | x | x | x | x | x | x | x |
| `void` | x | x | x | x | x | x | x | x | x | x | x |
| `mixed` | | | | x | x | x | x | x | x | x | x |
| `never` | | | | | x | x | x | x | x | x | x |
| Intersection types | | | | | x | x | x | x | x | x | x |
| `null` and `false` return types | | | | | | x | x | x | x | x | x |
| `true` literal return types | | | | | | x | x | x | x | x | x |
| PHP | 7.2 | 7.3 | 7.4 | 8.0 | 8.1 | 8.2 | 8.3 | 8.4 |
| [Relative class types](https://www.php.net/manual/en/language.types.relative-class-types.php) |
| `static` return-only type | | | | x | x | x | x | x | x |
| PHP | 7.2 | 7.3 | 7.4 | 8.0 | 8.1 | 8.2 | 8.3 | 8.4 |
| Trailing commas |
| [`use` statements](https://wiki.php.net/rfc/list-syntax-trailing-commas) | x | x | x | x | x | x | x | x | x | x |
| Trailing commas in Arrays | x | x | x | x | x | x | x | x | x |
| [Function calls](https://php.watch/versions/7.3/func-call-trailing-comma) | | x | x | x | x | x | x | x | x | x |
| [Function signatures](https://php.watch/versions/8.0/trailing-comma-parameter-use-list) | | | | x | x | x | x | x | x | x | x |
| PHP | 7.2 | 7.3 | 7.4 | 8.0 | 8.1 | 8.2 | 8.3 | 8.4 |
| [Arrow functions](https://www.php.net/manual/en/functions.arrow.php) | | | x | x | x | x | x | x | x | x | x |
| [Attributes](https://www.php.net/manual/en/language.attributes.php) | | | | x | x | x | x | x | x | x | x |
| [`match` expressions](https://www.php.net/manual/en/control-structures.match.php) | | | | x | x | x | x | x | x | x | x |
| [Constructor Property Promotion](https://www.php.net/manual/en/language.oop5.decon.php#language.oop5.decon.constructor.promotion) | | | | x | x | x | x | x | x | x | x |
| [Named parameters](https://php.watch/versions/8.0/named-parameters) | | | | x | x | x | x | x | x | x | x |
| [Enums](https://www.php.net/manual/en/language.enumerations.php) | | | | | x | x | x | x | x | x | x |
| [Readonly properties](https://www.php.net/manual/en/language.oop5.properties.php#language.oop5.properties.readonly-properties) | | | | | x | x | x | x | x | x | x |
| [`#[\SensitiveParameter]`](https://www.php.net/manual/en/class.sensitiveparameter.php) | | | | | | x | x | x | x | x |
| [Constants in traits](https://www.php.net/manual/en/migration82.new-features.php) | | | | | | x | x | x | x | x |
