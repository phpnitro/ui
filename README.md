# phpnitro/ui

Le moteur de rendu natif — widgets, layout, commandes Canvas, animations, gestes, et les classes d'API device (`Engine\Device\*`).

Fait partie de [PhpNitro](https://github.com/phpnitro/phpnitro) — un framework PHP qui compile vers de vraies apps Android natives (moteur de rendu Canvas, pas de WebView).

## Installation

```bash
composer require phpnitro/ui
```

## Usage

```php
use Engine\Native\{Container, Text};

$screen = new Container(
    new Text('Bonjour PhpNitro !', 20.0, '#111827'),
);
```

## Licence

MIT
