# DeAsciifier
PHP port of [Deniz Yuret's Turkish deasciifier](https://github.com/emres/turkish-mode).

- [ ] more tests
- [ ] upper character

## Installation

```sh
composer require quiec/deasciifier
```

## Usage

```php
require "vendor/autoload.php";
use DeAsciifier\DeAsciifier;
$Asciifer = new DeAsciifier();
print $Asciifer->DeAsciify("opusmeyi cagristiran citirtilar");
```

## License

MIT