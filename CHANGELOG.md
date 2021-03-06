# Poise-Python Changelog

## v1.2.0

* Add support for passing `user` and `group` to `pip_requirements`.
* Allow passing a virtualenv resource object to the `virtualenv` property.

## v1.1.2

* Fix `PythonPackage#response_file_variables` for the Chef 12.6 initializer.

## v1.1.1

* Fix passing options to the `python_package` resource.

## v1.1.0

* Add a `:dummy` provider for `python_runtime` for unit testing or complex overrides.
* Support installing development headers for SCL packages.
* Refactor Portable PyPy provider to use new helpers from `poise-languages`. This
  means `portable_pypy` and `portable_pypy3` are now separate providers but the
  auto-selection logic should still work as before.

## v1.0.0

* Initial release!

