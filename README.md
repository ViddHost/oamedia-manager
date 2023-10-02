Media manager for open-admin
===============================

 

Media manager for `local` disk.

[Documentation](http://open-admin.org/docs/en/extension-media-manager)
## Screenshot

![wx20170809-170104](http://open-admin.org/docs/images/screenshots/ext-media-manager.png)

## Installation

```shell
composer require ViddHost/oamedia-manager

php artisan admin:import media-manager
```

Add a disk config in `config/admin.php`:

```php

    'extensions' => [

        'media-manager' => [

            // Select a local disk that you configured in `config/filesystem.php`
            'disk' => 'public'
        ],
    ],

```


Open `http://localhost/admin/media`.

License
------------
Licensed under [The MIT License (MIT)](LICENSE).
