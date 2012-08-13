# SilverStripe Composer Autoload

This SilverStripe module loads before other SilverStripe modules (due to the name) and requires composers auto-generated `autoload.php` file if it exists.

Use this module if you want dependencies managed through composer to be available in your application earlier than it would if you required the `autoload.php` file in your `mysite/_config.php`.

## Usage in your `composer.json` file

    {
        "require": {
            "camspiers/autoloader-composer-silverstripe": "1.0.*"
        }
    }