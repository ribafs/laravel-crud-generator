# Laravel CRUD Generator

[![Build Status](https://travis-ci.org/appzcoder/crud-generator.svg)](https://travis-ci.org/appzcoder/crud-generator.svg)
[![Total Downloads](https://poser.pugx.org/appzcoder/crud-generator/d/total.svg)](https://packagist.org/packages/appzcoder/crud-generator)
[![Latest Stable Version](https://poser.pugx.org/appzcoder/crud-generator/v/stable.svg)](https://packagist.org/packages/appzcoder/crud-generator)
[![License](https://poser.pugx.org/appzcoder/crud-generator/license.svg)](https://packagist.org/packages/appzcoder/crud-generator)

This Generator package provides various generators like CRUD, API, Controller, Model, Migration, View for your painless development of your applications.

## Warning

If you have ribafs/crud-generator-acl installed please uninstall it before installing this ribafs/crud-generator.

This fork have changes to appzcoder/crud-generator:
- Change ```html<td>{{ $loop->iteration }}</td>``` to ```html<td>{{ $item->id }}</td>``` in src/stubs/views/html/index.blade.stub
- Add folder includes in publish/views
- and others

## Requirements
    Laravel >= 5.3
    PHP >= 5.6.4

## Installation
```
composer require ribafs/crud-generator --dev
```

## Documentation
Go through to the [detailed documentation](doc#readme)

## Screencast

[![Screencast](http://img.youtube.com/vi/831-PFBsYfw/0.jpg)](https://www.youtube.com/watch?v=K2G3kMQtY5Y)

#### If you're still looking for easier one then try this [Admin Panel](https://github.com/appzcoder/laravel-admin)

## Author

[Sohel Amin](http://sohelamin.com) :email: [Email Me](mailto:sohelamincse@gmail.com)

## License

This project is licensed under the MIT License - see the [License File](LICENSE) for details