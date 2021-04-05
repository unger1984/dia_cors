The CORS middleware for [Dia](https://github.com/unger1984/dia).

## Usage:

A simple usage example:

```dart
    app.use(cors());
```

## Named params:

* `origin` - Access-Control-Allow-Origin header. Default: '*'
* `maxAge` - Access-Control-Max-Age header
* `credentials` - Access-Control-Allow-Credentials header
* `expose` - Access-Control-Expose-Headers header

## Use with:

* [dia](https://github.com/unger1984/dia) - A simple dart http server in Koa2 style.
* [dia_router](https://github.com/unger1984/dia_router) - Middleware like as koa_router.
* [dia_body](https://github.com/unger1984/dia_body) - Package with the middleware for parse request body.
* [dia_static](https://github.com/unger1984/dia_static) - Package to serving static files.

## Features and bugs:

I will be glad for any help and feedback!
Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: https://github.com/unger1984/dia_cors/issues
