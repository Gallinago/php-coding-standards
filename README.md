# php-coding-standards
Custom PHP CS Rules

## Installation

Add the following to your `composer.json` file:

```
"repositories" : [
    {
        "type": "vcs",
        "url": "git@github.com:maciejslawik/php-coding-standards.git"
    }
]
```

Then run:

```
composer require maciejslawik/php-coding-standards:dev-master --dev
```

## Usage

Assuming you have phpcs installed:

```
./vendor/bin/phpcs -s /folder/to/code --standard=vendor/maciejslawik/php-coding-standards/MSlwk
```