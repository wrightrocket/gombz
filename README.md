GOMBZ
=====

This is a [Go][golang] library that provides a serializable data structure
for 3d models and animations.

Basically, it provides a set of data structures that represent 3d models, bones
and animations as well as functions to decode and encode them. The serialization
process uses BSON notation and then is run through [zlib][zlib-link].

UNDER CONSTRUCTION
==================

The library is currently in an alpha state, but you are welcome to see how
it's progressing.

Requirements
------------

This does require `cgo` which means that `gcc` should be in your path
when trying to build using this library.

Software requirements:

* [Mathgl][mgl] - for 3d math
* [BSON][bson-link] - a BSON implementation in Go for binary serialization


TODO
----

The following need to be addressed in order to start releases:

* documentation
* samples
* more data like animations


LICENSE
=======

Gombz is released under the BSD license. See the [LICENSE][license-link] file for more details.


[golang]: https://golang.org/
[license-link]: https://raw.githubusercontent.com/tbogdala/gombz/master/LICENSE
[mgl]: https://github.com/go-gl/mathgl
[bson-link]: http://gopkg.in/mgo.v2/bson
[zlib-link]: https://golang.org/pkg/compress/zlib/