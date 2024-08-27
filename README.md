# `::deinit`

> A collection of types and tools for delayed initialization of data.

---

This is similar to the [uninit](https://github.com/danielhenrymantilla/rust-uninit) crate,
in that it seeks to provide safe utilities for manipulating potentially uninitialized data.

However parts of the API seek to be closer to [tinyvec](https://github.com/Lokathor/tinyvec), providing
collection types, or extensions to existing collection types, that allow for incremental initialization
of their underlying data.


## Crate Name

I may change the name of this crate at some point in the future,
as `deinit` may indicate that it seeks to provide mechanisms for the deinitialization of data. 

While this is true, it is not all this crate does, and I think the current name is slightly
misleading.
