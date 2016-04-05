# Liblcm Rust Bindings

The `liblcm-sys` crate provides declarations and linkage for the `liblcm` C library. Following the
`*-sys` package conventions, the `liblcm-sys` crate does not define higher-level abstractions over
the native `liblcm` library functions.

## Dependencies
In order to use the `liblcm-sys` crate, you must have the `liblcm` library installed where it can be
found by `pkg-config`.

## Usage
Add `liblcm-sys` as a dependency in `Cargo.toml`:

```toml
[dependencies]
liblcm-sys = "1.3"
```

Import the `liblcm_sys` crate and use the functions as they're defined in the native `liblcm`
library. See the [`liblcm`C API documention](https://lcm-proj.github.io/group__LcmC__lcm__t.html) for more
usage information.

### Additional Resources
Since `liblcm-sys` is no more than a wrapper around the native `liblcm` library, the best source for
help is the information already available for `liblcm`:

* [Home Page](https://lcm-proj.github.io/)
* [API Documentation](https://lcm-proj.github.io/group__LcmC__lcm__t.html)
* [Source](https://github.com/lcm-proj/lcm)


## License
Copyright © 2015 Zac Berkowitz

Distributed under the [MIT License](LICENSE).
