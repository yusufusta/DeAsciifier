# DeAsciifier
PHP port of [Deniz Yuret's Turkish deasciifier](https://github.com/emres/turkish-mode).

- [ ] more tests
- [ ] upper character

## Installation
As a library:
```sh
composer require quiec/deasciifier
```
As an executable:
```sh
curl -L https://github.com/Quiec/DeAsciifier/releases/download/executable/deasciifier > /usr/local/bin/deasciifier && chmod +x /usr/local/bin/deasciifier
```

## Usage
As a library:
```php
require "vendor/autoload.php";
use DeAsciifier\DeAsciifier;
$Asciifer = new DeAsciifier();
print $Asciifer->DeAsciify("opusmeyi cagristiran citirtilar");
```

As an executable:
```sh
echo dunyali insan | deasciifier 
```

## License

MIT
