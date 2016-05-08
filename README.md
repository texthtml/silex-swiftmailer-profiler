# silex-swiftmailer-profiler

Provides Swiftmailer emails logging for [Silex Web Profiler](https://github.com/silexphp/Silex-WebProfiler) 

## Installation

Install the silex-swiftmailer-profiler using [composer](http://getcomposer.org/). 

```bash
composer require texthtml/silex-swiftmailer-profiler "^2.0@dev"
```

## Registering

```php
$app->register(new \TH\SilexSwiftmailerProfiler\SwiftmailerProfilerServiceProvider());
```

Be sure to do this after registering `WebProfilerServiceProvider`.
