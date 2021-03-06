# A web app from scratch

Supporting material for my blog post series on writing a web
application from scratch in Python.

You'll need Python 3.6+ to run any of this code.  Start by reading
`scratch/server.py`.  Run the application with `python -m scratch`.


# Tags

There is a tag for each part of the series:

1. [`part-01`][part-1] -- A simple file server.
1. [`part-02`][part-2] -- Abstractions!
1. [`part-03`][part-3] -- Handlers and Middleware.
1. [`part-04`][part-4] -- Application and Router.
1. `part-05` -- Coming soon...


[part-1]: https://defn.io/2018/02/25/web-app-from-scratch-01/
[part-2]: https://defn.io/2018/03/04/web-app-from-scratch-02/
[part-3]: https://defn.io/2018/03/20/web-app-from-scratch-03/
[part-4]: https://defn.io/2018/05/12/web-app-from-scratch-04/


## Type-checking

This repo uses Python 3 type annotations which can be type-checked
using [mypy].  Run `pip install mypy` and then `mypy scratch` to
type check the code.


## Testing

Run `pip install pytest` and then `py.test`.


## License

web-app-from-scratch is licensed under Apache 2.0.  Please see
[LICENSE] for licensing details.


[LICENSE]: https://github.com/Bogdanp/falcon_sugar/blob/master/LICENSE
[mypy]: https://mypy.readthedocs.io
