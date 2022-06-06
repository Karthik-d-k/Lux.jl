# v0.4

## v0.4.4

* `Chain` allows custom naming for its sublayers
* `Dropout` Layers caches `1 / (1 - p)` for minor improvements for forward pass
* `dropout` has a custom rrule -- significantly improves performance for smaller arrays

## v0.4.3

* Extending Scale to allow for multiple dimension inputs (https://github.com/avik-pal/Lux.jl/pull/40)

## v0.4.2

* `SelectDim` is no longer type unstable -- Internal storage for the Layer has been changed
* `Dropout` & `VariationalDropout` return `NoOpLayer` if the probability of dropout is `0`
* Code Formatting -- SciMLStyle (https://github.com/avik-pal/Lux.jl/pull/31)

## v0.4.1

* Fix math rendering in docs
* Add Setfield compat for v1.0