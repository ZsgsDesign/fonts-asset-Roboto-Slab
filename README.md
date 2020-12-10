# fonts-asset-Roboto-Slab
Roboto-Slab for composer.

## Install

```bash
composer require oomphinc/composer-installers-extender
composer require fonts-asset/roboto-slab
```

And in `composer.json`:

```json
    "extra": {
        "installer-types": [
            "fonts-asset"
        ],
        "installer-paths": {
            "public/fonts/{$name}": [
                "type:fonts-asset"
            ]
        }
    },
```

## Usage

```html
<link rel="stylesheet" href="/fonts/roboto-slab/roboto-slab.css">
```

## Credit

[Google Fonts](https://fonts.google.com/)