# php-coding-standards
Custom PHP CS Rules by Gallinago

## Installation

Add the following to your `composer.json` file:

```
"repositories" : [
    {
        "type": "vcs",
        "url": "git@github.com:gallinago/php-coding-standards.git"
    }
]
```

Then run:

```
composer require gallinago/php-coding-standards:dev-master --dev
```

## Usage

Assuming you have phpcs installed:

```
./vendor/bin/phpcs -s /folder/to/code --standard=vendor/gallinago/php-coding-standards/Gallinago
```